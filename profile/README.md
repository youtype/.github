# YouType

You type, we autocomplete!

Use type checking and code completion to write more readable, maintainable code for [AWS](https://aws.amazon.com/) using [Python](https://www.python.org/).
Type annotations are compatible with
[VSCode](https://code.visualstudio.com/),
[PyCharm](https://www.jetbrains.com/pycharm/),
[Emacs](https://www.gnu.org/software/emacs/),
[Sublime Text](https://www.sublimetext.com/),
[mypy](https://github.com/python/mypy),
[pyright](https://github.com/microsoft/pyright)
and other tools.

| Project | Library | Docs | PyPI | Conda | VSCode | Support |
|-|-|-|-|-|-|-|
| [boto3-stubs](https://pypi.org/project/boto3-stubs/) | [boto3](https://pypi.org/project/boto3/) | [📃](https://youtype.github.io/boto3_stubs_docs/) | [boto3-stubs](https://pypi.org/project/boto3-stubs/) | [boto3-stubs](https://anaconda.org/conda-forge/boto3-stubs) / [boto3-stubs-essential](https://anaconda.org/conda-forge/boto3-stubs-essential) | [Boto3 IDE](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide&ssr=false) | [mypy_boto3_builder](https://github.com/youtype/mypy_boto3_builder) |
| [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) | [aiobotocore](https://pypi.org/project/aiobotocore/) | [📃](https://youtype.github.io/types_aiobotocore_docs/) | [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) | | | [mypy_boto3_builder](https://github.com/youtype/mypy_boto3_builder) |
| [types-aioboto3](https://pypi.org/project/types-aioboto3/) | [aioboto3](https://pypi.org/project/aioboto3/) | [📃](https://youtype.github.io/types_aioboto3_docs/) | [types-aioboto3](https://pypi.org/project/types-aioboto3/) | | | [mypy_boto3_builder](https://github.com/youtype/mypy_boto3_builder) |
| [botocore-stubs](https://pypi.org/project/botocore-stubs/) | [botocore](https://pypi.org/project/botocore/) | | [botocore-stubs](https://pypi.org/project/botocore-stubs/) | [botocore-stubs](https://anaconda.org/conda-forge/botocore-stubs) | [Boto3 IDE](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide&ssr=false) | [botocore-stubs](https://github.com/youtype/botocore-stubs) |
| [types-s3transfer](https://pypi.org/project/types-s3transfer/) | [s3transfer](https://pypi.org/project/s3transfer/) | | [types-s3transfer](https://pypi.org/project/types-s3transfer/) | [types-s3transfer](https://anaconda.org/conda-forge/types-s3transfer) | [Boto3 IDE](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide&ssr=false) | [types-s3transfer](https://github.com/youtype/types-s3transfer) |
| [types-awscrt](https://pypi.org/project/types-awscrt/) | [awscrt](https://pypi.org/project/awscrt/) | | [types-awscrt](https://pypi.org/project/types-awscrt/) | | [Boto3 IDE](https://marketplace.visualstudio.com/items?itemName=Boto3typed.boto3-ide&ssr=false) | [types-awscrt](https://github.com/youtype/types-awscrt) |

## Projects

### mypy_boto3_builder

[GitHub](https://github.com/youtype/mypy_boto3_builder)

Type annotations builder for boto3-stubs project. Compatible with VSCode, PyCharm, Emacs, Sublime Text, mypy, pyright and other tools.

### AWS CLI v2 for Python

[GitHub](https://github.com/youtype/awscliv2)

Wrapper for AWS CLI v2.

### iStub

[GitHub](https://github.com/youtype/istub)

Validator for type annotations.

## Heartbeat

[![boto3-stubs consistency](https://github.com/youtype/mypy_boto3_builder/actions/workflows/consistency_check.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/consistency_check.yml)
[![boto3-stubs sanity](https://github.com/youtype/mypy_boto3_builder/actions/workflows/sanity_check.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/sanity_check.yml)
[![boto3-stubs integration](https://github.com/youtype/mypy_boto3_builder/actions/workflows/integration.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/integration.yml)

[![types-aiobotocore consistency](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_consistency_check.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_consistency_check.yml)
[![types-aiobotocore sanity](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_sanity_check.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_sanity_check.yml)
[![types-aiobotocore integration](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_integration.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/aio_integration.yml)

[![Publish boto3-stubs](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_boto3_stubs.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_boto3_stubs.yml)
[![Publish types-aiobotocore](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_aiobotocore_stubs.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_aiobotocore_stubs.yml)
[![Publish types-aioboto3](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_types_aioboto3.yml/badge.svg)](https://github.com/youtype/mypy_boto3_builder/actions/workflows/publish_types_aioboto3.yml)

[![Publish botocore-stubs](https://github.com/youtype/botocore-stubs/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/botocore-stubs/actions/workflows/publish_on_update.yml)
[![Publish types-awscrt](https://github.com/youtype/types-awscrt/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/types-awscrt/actions/workflows/publish_on_update.yml)
[![Publish types-s3transfer](https://github.com/youtype/types-s3transfer/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/types-s3transfer/actions/workflows/publish_on_update.yml)

[![Update boto3-stubs docs](https://github.com/youtype/boto3_stubs_docs/actions/workflows/update.yml/badge.svg)](https://github.com/youtype/boto3_stubs_docs/actions/workflows/update.yml)
[![Update types-aiobotocore docs](https://github.com/youtype/types_aiobotocore_docs/actions/workflows/update.yml/badge.svg)](https://github.com/youtype/types_aiobotocore_docs/actions/workflows/update.yml)
[![Update types-aioboto3 docs](https://github.com/youtype/types_aioboto3_docs/actions/workflows/update.yml/badge.svg)](https://github.com/youtype/types_aioboto3_docs/actions/workflows/update.yml)

[![Publish boto3-stubs](https://github.com/youtype/boto3-stubs/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/boto3-stubs/actions/workflows/publish_on_update.yml)
[![Publish types-aiobotocore](https://github.com/youtype/types-aiobotocore/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/types-aiobotocore/actions/workflows/publish_on_update.yml)
[![Publish types-aioboto3](https://github.com/youtype/types-aioboto3/actions/workflows/publish_on_update.yml/badge.svg)](https://github.com/youtype/types-aioboto3/actions/workflows/publish_on_update.yml)