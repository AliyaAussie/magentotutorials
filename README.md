# Vanilla Magento Decomposed

This repo is a vanill ainstall of magento but has core modules, design, skins, js, libs etc striopped out and composered in.

## Install

* Clone or fork the repo and play around.
* Boxen - `include projects::magento::decomposed::v1-14-2-1`

If you use boxen you might expect a `app/etc/local.xml` to be created but it will have been removed.

* Setup database
  * `mysql -uroot`
  * `create data {senesible_db_name}`
* Run install wizard
  * http://vanilla-decomposed-magento-1-14-2-1.dev
  * Fill in the wizard
    * DB Host - `127.0.0.1:13306`
    * DB User - `root`
    * DB Password - leave blank


## Usage

Use this to play around with magento bugs or sandbox development 

*Don't* commit to this repository unless you find a bug in the vanilla magento install.
