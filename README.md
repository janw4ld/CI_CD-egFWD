## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](pipeline.png)
___
### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01](https://github.com/janw4ld/CI_CD-egFWD)
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02](http://udapeople-a25da79.s3-website-us-east-1.amazonaws.com)
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03](http://d3ibvx0yfd6z8u.cloudfront.net)
  1. Public URLs to deployed application back-end in EC2 [URL04](http://54.91.122.201:3030/api/status)
  1. Public URL to your Prometheus Server [URL05](http://ec2-44-202-141-5.compute-1.amazonaws.com:9090/targets)
</br><sup>The links are broken now, because the infrastructure was destroyed after completing the project.</sup>

- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions.
  1. Job failed because of compile errors. [SCREENSHOT01](udacity/submission/SCREENSHOT01.png)
  2. Job failed because of unit tests. [SCREENSHOT02](udacity/submission/SCREENSHOT02.png)
  3. Job that failed because of vulnerable packages. [SCREENSHOT03](udacity/submission/SCREENSHOT03.png)
  4. An alert from one of your failed builds. [SCREENSHOT04](udacity/submission/SCREENSHOT04.png)
  5. Appropriate job failure for infrastructure creation. [SCREENSHOT05](udacity/submission/SCREENSHOT05.png)
  6. Appropriate job failure for the smoke test job. [SCREENSHOT06](udacity/submission/SCREENSHOT06.png)
  7. Successful rollback after a failed smoke test. [SCREENSHOT07](udacity/submission/SCREENSHOT07.png)  
  8. Successful promotion job. [SCREENSHOT08](udacity/submission/SCREENSHOT08.png)
  9. Successful cleanup job. [SCREENSHOT09](udacity/submission/SCREENSHOT09.png)
  10. Only deploy on pushed to `master` branch. [SCREENSHOT10](udacity/submission/SCREENSHOT10.png)
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. </br><sup>Note that 3 screenshots are required i.e. [node free memory](udacity/submission/SCREENSHOT11_memory.png), [node CPU usage](udacity/submission/SCREENSHOT11_cpu.png), and [node disk usage](udacity/submission/SCREENSHOT11_disk.png).</sup>
  12. Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12](udacity/submission/SCREENSHOT12.png)

- Your presentation should be in PDF format and named [presentation.pdf](udacity/submission/presentation.pdf).

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
