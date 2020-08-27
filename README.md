# docker_konlpy_django

Django & Konlpy combine docker image for AWS deployment

## Installation && Usage

```bash
docker image build .
```

or

```
docker image pull snoop2head/django_konlpy_postgres
```



## Structure

![image-20200422145948905](src/image-20200422145948905.png)

OS is Ubuntu latest verision

* JRE/JDK on top of Ubuntu
  * KoNLPy's dependency
* Python3 and pip3 on top of Ubuntu
  * Django and its dependencies
  * KoNLPy
  * psycopg2-binary for PostgreSQL DB connection

