COPY beta5-istidafa-main/requirements.txt ./
RUN pip install -r requirements.txt

COPY beta5-istidafa-main/istidafa4_by_moon.py \
     beta5-istidafa-main/keepalive.py \
     beta5-istidafa-main/botconfig.py \
     beta5-istidafa-main/serverinfo.py \
     beta5-istidafa-main/countries_ar.py ./

COPY beta5-istidafa-main/.env.example ./.env.example

COPY beta5-istidafa-main/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh
