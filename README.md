# ESP-IDF Docker image with Clang

Adds the following features on top of `espressif/idf`:

- [esp-clang](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/tools/idf-tools.html#esp-clang)
- [IDF SBOM](https://docs.espressif.com/projects/esp-idf/en/stable/esp32/api-guides/tools/idf-sbom.html)
- [spdx-tools](https://github.com/spdx/tools)

Use the [GitHub Actions workflow](https://github.com/lptr/esp-idf-clang-docker/actions/workflows/build.yml) to build and deploy for the desired versions of ESP-IDF.
Find available tags among [ESP-IDF releases](https://github.com/espressif/esp-idf/releases).
