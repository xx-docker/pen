FROM python:3.6

ARG INSTALL_PATH=/software
RUN mkdir -p ${INSTALL_PATH}
WORKDIR ${INSTALL_PATH}

RUN git clone https://github.com/xmendez/wfuzz && cd wfuzz && \
pip install -r requirements.txt --index-url https://pypi.tuna.tsinghua.edu.cn/simple && python setup.py install 

WORKDIR ${INSTALL_PATH}/wfuzz

