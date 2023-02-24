# smarty

This extension will switch your site to use Smarty v3, but
only if you add a define to your `civicrm.settings.php` - eg

`define('CIVICRM_SMARTY_SRC', '/srv/civi-sites/dmaster/web/sites/all/modules/civicrm/ext/smarty/vendor/autoload.php');`

Otherwise no change will occur.


## Requirements

* PHP v7.4+
* CiviCRM 5.60

## Installation (Web UI)

Learn more about installing CiviCRM extensions in the [CiviCRM Sysadmin Guide](https://docs.civicrm.org/sysadmin/en/latest/customize/extensions/).

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl smarty@https://github.com/eileenmcnaughton/smarty/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/eileenmcnaughton/smarty.git
cv en smarty
```

## Getting Started
In order to use Smarty3 you must add the define at the
top of this readme

## Known Issues

Many - see https://lab.civicrm.org/dev/core/-/issues/4146
