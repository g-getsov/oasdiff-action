FROM tufin/oasdiff:main
ENV PLATFORM github-action
COPY $GITHUB_WORKSPACE/common /common
COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]