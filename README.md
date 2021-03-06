# Official Code Repository of B.Tech. Project 

This is the repository for Traffic Sign Recognition

## Demo Links

|                                                                                          <b>Post Evaluation UI</b>                                                                                |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
<a href="https://youtu.be/RDlAl-uT918" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/RDlAl-uT918/default.jpg" alt="Post Experiment Evaluation UI"></a> |

## Set-up instructions

### Pre-requisites

1. Install `Docker` (>= `v20.10.5`) by looking up the
   [docs](https://docs.docker.com/get-docker/)
2. Install `Docker Compose` (>= `v1.28.2`) by looking up the
   [docs](https://docs.docker.com/compose/install/)

### Steps

1. Unzip the file `BTech-Project-main.zip`.
2. Run `cd BTech-Project-main/` to change directory.
3. Run `docker-compose up --build` to spin up the containers.
4. Web interface would then be available locally at [`http://localhost:3000`](http://localhost:3000).

### Usage info

1. Baseline Model can be downloaded from [this link](https://drive.google.com/file/d/19HdNYmaXwmDZMWviMV6rh8BqdVGexxqp/view?usp=sharing) (This model can be uploaded in the Post-evaluation UI)
2. Sample train and test datasets have been attached in `services/server/train-dataset` and `services/server/test-dataset` respectively. (They will be mounted to the docker container as volumes)

---

## File Structure

- **Detailed project report** has been attached as `PROJECT_REPORT.pdf`.
- ML Training workflow has been attached in `Resnet_training.ipynb` and `Efficient net_training.ipynb`   
- Backend code has been attached in `services/server/`.
- Frontend code has been attached in `services/web/`.
