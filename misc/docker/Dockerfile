FROM alumae/kaldi-align-server@sha256:c4a4e8f29e40f211124db39ae72a9141d2b19d277ed8a370542147d30ba55ff1

MAINTAINER Juho Leinonen <juho.leinonen@aalto.fi>

COPY align.sh /opt/kaldi-align-server/aligner/align.sh

WORKDIR aligner

ENTRYPOINT ["./align.sh"]
