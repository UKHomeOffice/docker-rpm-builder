# Docker RPM Builder

A Docker image to build rpms, includes ruby, fpm and rpmbuild.

### Usage

docker run -it -v ${PWD}:${PWD} -w ${PWD} quay.io/ukhomeofficedigital/rpm-builder:v0.1 <build rpm script>

## Contributing

Contributions are most certainly welcome. If you want to introduce a breaking
change or any other major change, please raise an issue first to discuss.
