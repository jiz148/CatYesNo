# Python Machine Learning

> Machine-learning practice includes classifier, and etc.



<br /><a name="contents"></a>
## Contents

* [Classifier](./classifier)
* [Project Setup](#setup)
* [Start](#start)


<br /><a name="setup"></a>
## Setup

### Cleaning-up

  ```
  make clean
  ```


### Dev Setup

  Set up Python [venv](https://docs.python.org/3/library/venv.html) before running anything:

  ```
  make dev-setup
  ```


<br /><a name="start"></a>
## Start

### Classifier

  * Run training:

    ```
    make ctr  # or run `(cd ml/classifier; make training)`
    ```

  * Run prediction:

    ```
    make cpr  # or run `(cd ml/classifier; make prediction)`
    ```
