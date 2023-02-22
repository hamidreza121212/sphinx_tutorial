# Checking packages is installed


python
---------------

> python --version


pip
---------------

> pip --version

upgrade pip
---------------

> python.exe -m pip install --upgrade pip


install poetry
---------------

> pip install poetry

poetry cheking 
---------------

> poetry --version

insert poetry
---------------
> poetry init


poetry set
---------------
> poetry install


poetry activate env
---------------
> poetry shell


# sphinx installation


sphinx install on pip
---------------
> pip install -U sphinx


set chocolatey path in envirment for windows
---------------
> @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"


make is available on chocolatey.
---------------
> choco install make


# sphinx config


create docs folder
---------------

> mkdir docs



start sphinx 
---------------

> cd docs
>> sphinx-quickstart



sphinx run modules
---------------
> sphinx-apidoc -o ./docs/sours .



sphinx install theme
---------------
> poetry add sphinx_rtd_theme