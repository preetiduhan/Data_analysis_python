why virtual environment?
suppose we have two projects: 
dev and test.dev requires 2.3 version of x package and test requires 3.1 version of x package.If we install 2.3 at sysetm level then 
dev will work but test will not work.So it is always better to use virtual environment:Now projects will handle dependencies at project
level so no system level conflicts will occur.

Steps to create virtual environment:

python -m venv /home/preeti/data-analysis/venv------------To create virtual environment,python3 provides venv module

source venv/bin/activate----------------------------------To activate virtual environment

which python
/home/preeti/data-analysis/venv/bin/python----------------after activating virtual environment

deactivate -----------------------------------------------deactivate virtual environment

which python
/usr/bin/python------------------------------------------Now This points to system level package

