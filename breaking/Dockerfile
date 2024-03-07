FROM tufin/oasdiff:main
ENV PLATFORM github-action
COPY $GITHUB_WORKSPACE/common com
COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]