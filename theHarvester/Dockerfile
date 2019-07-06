FROM python:3.6

ARG INSTALL_PATH=/software
RUN mkdir -p ${INSTALL_PATH}
WORKDIR ${INSTALL_PATH}

RUN git clone https://github.com/laramies/theHarvester cd theHarvester && \
pip install -r requirements.txt --index-url https://pypi.tuna.tsinghua.edu.cn/simple

WORKDIR ${INSTALL_PATH}/theHarvester

CMD ['python', 'theHarvester.py']

