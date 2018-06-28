docker login https://docker.willclark.org
docker build . --tag "docker.willclark.org/willclark_org:${VERSION}"
docker push docker.willclark.org/willclark_org:${VERSION}
docker logout https://docker.willclark.org