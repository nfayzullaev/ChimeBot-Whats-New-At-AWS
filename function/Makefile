PIP=pip3
PACKAGE=teamsbot-whatsnew.zip
ZIP=zip

all: deps
	$(ZIP) -r $(PACKAGE) *

deps:
	$(PIP) install -t . requests feedparser bs4
