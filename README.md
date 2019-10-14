# Airflow: your ally for automating machine learning and data pipelines

### PyCon DE & PyData Berlin // 10th October 2019

#### E. Pasqua, B. Uyarer @ [Delivery Hero](https://www.deliveryhero.com)

<img src="/media/airflow_logo.png" align="right" width="35%">

<br />**Orchestrating, scheduling and monitoring ML pipelines** is a big challenge.<br /> **[Apache Airflow](https://airflow.apache.org)** can be your ally for handling this complexity.

Apache Airflow is an open source project written in Python for programmatically author, schedule and monitor batch execution of tasks.

You can design your pipelines according to a determined logic: decide which actions to perform, retry them if errors occur, skip tasks if dependencies are not met, access monitor and log status through a friendly and powerful web UI, and a lot more.

In **this workshop** we’ll go over **basic Airflow concepts** and we’ll setup an instance **for orchestrating a training and an inference pipeline** for a machine learning model.


#### Details for Audience
* It assumes no previous Airflow knowledge.
* The main purpose is creating a **basic** train and inference pipeline with Airflow.
* It is not about a particular model / ML method.
* It's not an advanced Airflow workshop.
* It is not suitable for Python beginners.

#### Workshop Requirements
* **[Docker installed](https://www.docker.com/)**.
* Any editor (Sublime, PyCharm, Vim, Atom).
* [Verify that Docker works properly](https://docs.docker.com/get-started/part2/): `docker run hello-world`
* **Ensure that you allocated 4gb of RAM for the Docker Engine**. (Can be done via desktop app, check Preferences section. After setting up, restart Docker App)
* **Download the Airflow Docker image**: `docker pull puckel/docker-airflow`
* Download repository under the `$HOME` directory.
`git clone https://github.com/enricapq/pyconde2019-airflow-ml-workshop`

Note: Airflow installation and setup (without using Docker) are provided as appendix files ([Mac OS X Airflow Setup](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/mac_os_x_airflow_setup.md), [Ubuntu Airflow Setup](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/ubuntu_airflow_setup.md)).

During the tutorial we assume that everyone follows the steps tailored for using a containerised version of Airflow.

You can find the [official Airflow documentation here](https://airflow.incubator.apache.org/).

-------

## Table of contents
- [Docker Airflow Setup](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/docker_airflow_setup.md)
- [Airflow main concepts](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/airflow_main_concepts.md)
<a href="https://www.deliveryhero.com"><img src="/media/delivery_hero_logo.png" alt="Delivery Hero" align="right" style="margin-right: 25px" height=120></a>
- [Exercises: Airflow for training and predicting](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/exercise_intro.md)
- [EX 1. Preconditions: Variables, Tables and Connection](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/exercise_1.md)
- [EX 2. Train the model](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/exercise_2.md)
- [EX 3. Prediction](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/exercise_3.md)
- [Bonus EX. Plot Predictions](https://github.com/enricapq/pyconde2019-airflow-ml-workshop/blob/master/exercise_4.md)
<br />

-------

<p align="center">
<img src="media/pyconde_pydata_2019_airflow.jpg" alt="ex3" width="100%"/>
</p>
