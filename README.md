PRGIT Fee
=========

## Installation ##

Need use Python version more than 3.4.

Steps:

* sudo apt-get install libxml2-dev libxslt1-dev python3-pip
* pip3 install $(cat ./requires.txt)

## Execution ##

    python3 -m fee


## ENV variables ##

To see files .env

    PYTHON_BIN_FILE - (by default: python3)

    PRGIT_FEE_STAT_URL - (by default: http://www.belstat.gov.by/ofitsialnaya-statistika/solialnaya-sfera/trud/operativnaya-informatsiya_8/o-nachislennoi-srednei-zarabotnoi-plate-rabotnikov/)
    PRGIT_FEE_STAT_KEY - (by default: информационные технологии и деятельность в области информационного обслуживания)
    PRGIT_FEE_STAT_PERCENT_URL - (by default: http://www.belstat.gov.by/ofitsialnaya-statistika/makroekonomika-i-okruzhayushchaya-sreda/tseny/godovye-dannye_3/indeksy-tsen-i-tarifov/)
    PRGIT_FEE_STAT_PERCENT_KEY - (by default: Индекс потребительских цен)
    PRGIT_FEE_STAT_YEAR - (by default current year)

    PRGIT_FEE_PERCENT - (by default: 1.0)
    PRGIT_FEE_FILE - (by default file path on server)
