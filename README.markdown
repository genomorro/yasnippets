# YaSnippets collection

Comprehensive collection of snippets that have been collected from
many people.

Included modes from rejeep are:

* clojure-mode
* css-mode
* emacs-lisp-mode
* feature-mode
* haml-mode
* haskell-mode
* html-mode
* rhtml-mode
* java-mode
* js-mode
* js2-mode
* nxml-mode
* ruby-mode
* sass-mode
* sh-mode

Other modes:

* latex-mode (for linguistics)
* sql-mode

Add to yout .emacs: 

(setq yas-snippet-dirs
      (append '("~/.emacs.d/snippets/genomorro"
		"~/.emacs.d/snippets/rejeep"
		) yas-snippet-dirs))
