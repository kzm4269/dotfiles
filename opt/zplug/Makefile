ZPLUG_HOME := $(HOME)/.zplug

.SUFFIXES:

.PHONY:
install: $(ZPLUG_HOME)
	zsh $(ZPLUG_HOME)/init.zsh

.PHONY:
deploy:

.PHONY:
update:
	@cd $(ZPLUG_HOME) && git pull

.PHONY:
clean:

$(ZPLUG_HOME):
	git clone https://github.com/zplug/zplug $@ 
