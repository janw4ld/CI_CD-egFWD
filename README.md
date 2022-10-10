## egFWD Advanced Cloud DevOps project 3:
# Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

## CI/CD Pipeline Diagram
![pipeline diagrams.](pipeline.png)
___
### Project specifications

- A text file named `urls.txt` including:
  </br><sup>Note that the URLs are broken now, because the infrastructure was destroyed after completing the project.</sup>
  | Specifications | Proof | Meets specifications |
  |---|---|---|
  | Public Url to GitHub repository (not private) | [URL01](https://github.com/janw4ld/CI_CD-egFWD) | ✓ |
  | Public URL for your S3 Bucket (aka, your green candidate front-end) | [URL02](http://udapeople-a25da79.s3-website-us-east-1.amazonaws.com) | ✓ |
  | Public URL for your CloudFront distribution (aka, your blue production front-end) | [URL03](http://d3ibvx0yfd6z8u.cloudfront.net) | ✓ |
  | Public URLs to deployed application back-end in EC2 | [URL04](http://54.91.122.201:3030/api/status) | ✓ |
  | Public URL to your Prometheus Server | [URL05](http://ec2-44-202-141-5.compute-1.amazonaws.com:9090/targets) | ✓ |

- Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions.
  | Specifications | Proof | Meets specification |
  |---|---|---|
  | Job failed because of compile errors. | [SCREENSHOT01](udacity/submission/SCREENSHOT01.png) | ✓ |
  | Job failed because of unit tests. | [SCREENSHOT02](udacity/submission/SCREENSHOT02.png) | ✓ |
  | Job that failed because of vulnerable packages. | [SCREENSHOT03](udacity/submission/SCREENSHOT03.png) | ✓ |
  | An alert from one of your failed builds. | [SCREENSHOT04](udacity/submission/SCREENSHOT04.png) | ✓ |
  | Appropriate job failure for infrastructure creation. | [SCREENSHOT05](udacity/submission/SCREENSHOT05.png) | ✓ |
  | Appropriate job failure for the smoke test job. | [SCREENSHOT06](udacity/submission/SCREENSHOT06.png) | ✓ |
  | Successful rollback after a failed smoke test. | [SCREENSHOT07](udacity/submission/SCREENSHOT07.png) | ✓ |  
  | Successful promotion job. | [SCREENSHOT08](udacity/submission/SCREENSHOT08.png) | ✓ |
  | Successful cleanup job. | [SCREENSHOT09](udacity/submission/SCREENSHOT09.png) | ✓ |
  | Only deploy on pushed to `master` branch. | [SCREENSHOT10](udacity/submission/SCREENSHOT10.png) | ✓ |
  | Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. </br><sup>Note that 3 screenshots are required | [node free memory](udacity/submission/SCREENSHOT11_memory.png), [node CPU usage](udacity/submission/SCREENSHOT11_cpu.png), [node disk usage](udacity/submission/SCREENSHOT11_disk.png).</sup> | ✓ |
  | Provide a screenshot of an alert that was sent by Prometheus. | [SCREENSHOT12](udacity/submission/SCREENSHOT12.png) | ✓ |

- Your presentation should be in PDF format and named [presentation.pdf](udacity/submission/presentation.pdf). ✓
___
### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
