# Kubernetes on AWS Users

If you are using Kubernetes on AWS, please [participate in our Kubernetes on AWS user survey](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform)
to help us compile a public list of Kubernetes on AWS users.

The survey results (list of organizations) will be published in the next section.

## Form Responses

The following companies/organizations filled out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform) so far (sorted alphabetically):

<!-- TABLE_START -->
| Organization | Workload (K8s on AWS) | Provisioning | More Info | Location |
|---|---|---|---|---|
| [AOE](https://aoe.com) | dev/test/staging | kops |  | Wiesbaden, Germany |
| [Applatix, Inc.](https://www.applatix.com) | dev/test/staging | kube-up | Yes. See https://applatix.com/blog/ for various articles on our internal use | Sunnyvale, California. |
| [Athlinks](https://www.athlinks.com) | critical business apps | kubeadm, Terraform | https://twitter.com/ryanckoch/status/768933690298609665 https://prezi.com/goiqe5_2u7lg/not-all-who-wander-are-lost-our-journey-to-kubernetes/ | Louisville, CO |
| [Box](http://www.box.com) | proof of concept | kops |  | Redwood City, CA |
| [Checkr](http://checkr.com) | critical business apps | kube-aws | https://github.com/checkr/fluentd-firehose  and more to come.. | San Francisco, CA |
| [Clarifai, Inc.](https://clarifai.com) | critical business apps | Custom Ansible for GPUs + CoreOS | http://blog.clarifai.com/how-to-scale-your-gpu-cloud-infrastructure-with-kubernetes/ | New York City (HQ), San Francisco |
| [CodeValue](http://www.codevalue.net) | critical business apps | kops |  | Israel |
| [Descomplica](https://descomplica.com.br) | critical business apps | kube-aws | http://danielfm.me/posts/five-months-of-kubernetes.html | Rio de Janeiro, Brazil |
| [Deutsche Börse Group](http://deutsche-boerse.com) | proof of concept | kops |  | Prague, Czech Republic / Frankfurt, Germany |
| [Engine Yard](http://engineyard.com) | critical business apps | new product | Coming soon | San Francisco, CA |
| [Exaring AG](http://waipu.tv) | critical business apps | kops, Home build solution |  | München, Karlsruhe, Berlin |
| [immmr GmbH](http://www.immmr.com) | critical business apps | Custom terraform + Container Linux | https://www.slideshare.net/Metatron31/kubernetes-at-immmr-coreos-fest-2016 | Berlin, Germany |
| [Luiza Labs](http://luizalabs.com) | critical business apps | kops | Our first Black Friday with critical apps on Kubernetes: http://schd.ws/hosted_files/cloudnativeeu2017/10/KubeCon-BlackFriday.pdf | São Paulo, Brazil |
| [Movio](https://movio.co/) | critical business apps | Custom Ubuntu AMIs | Older blog post: https://movio.co/blog/6-months-kubernetes-production/ Prometheus + Kubernetes: https://movio.co/blog/prometheus-service-discovery-kubernetes/ | Auckland, New Zealand |
| [Photobox Ltd](http://group.photobox.com) | critical business apps | kops |  | London |
| [SeamlessGov](http://seamlessgov.com/) | critical business apps | kops |  | New York, NY |
| [Spire Labs](http://spirelabs.co (also spire.me)) | critical business apps | kops | https://medium.com/spire-labs/mitigating-an-aws-instance-failure-with-the-magic-of-kubernetes-128a44d44c14 https://www.youtube.com/watch?v=xvXy2BiaWrQ | Chattanooga, TN |
| [Spotahome](http://www.spotahome.com) | critical business apps | kops | Not yet | Madrid, Spain |
| [Spreaker](https://www.spreaker.com) | critical business apps | kops |  | Remote Team across Europe |
| [store2be GmbH](https://tech.store2be.com) | internal/non-critical apps | kops |  | Berlin, Germany |
| [Stylight GmbH](https://www.stylight.com) | critical business apps | Custom Cloud Formation + CoreOS | https://github.com/stylight/etcd-bootstrap | Munich |
| [Ticketmaster](http://www.ticketmaster.com) | critical business apps | CoreOS Tectonic | See presentations from KubeCon & KubeCon EU. It's growing like mad. | Los Angeles, CA |
| [uSwitch](http://www.uswitch.com) | critical business apps | kops and custom terraform | Not yet- we've started posting regularly to https://labs.uswitch.com and some posts on our Kubernetes work will appear soon. | London, UK |
| [Veritas Technologies LLC](http://veritas.com) | internal/non-critical apps | Terraform based on kube-aws with CoreOS | No | Minneapolis, MN; Hays, KS; Mtn View, CA |
| [Vonage](https://www.vonage.com) | proof of concept | kops, terraform |  | Holmdel, NJ |
| [Weaveworks](http://weave.works) | critical business apps | Terraform+Ansible (https://github.com/weaveworks/ansible-kubernetes) | https://www.weave.works/provisioning-lifecycle-production-ready-kubernetes-cluster/ | Berlin, London & San Francisco |
| [Zalando SE](https://tech.zalando.com) | critical business apps | Custom Cloud Formation + CoreOS | https://github.com/zalando-incubator/kubernetes-on-aws | Berlin, Germany |
<!-- TABLE_END -->


## Manually Compiled List

The following companies/organizations are known to run Kubernetes on AWS (sorted alphabetically), but haven't yet filled out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform):

* [Base CRM](https://getbase.com) (lab: [BaseLab](https://lab.getbase.com))
* [Buffer](https://buffer.com)
* Concur
* Disney
* [GolfNow](https://www.youtube.com/watch?v=MBDog4ivBHI&list=PLj6h78yzYM2PqgIGU1Qmi8nY7dqn9PCr4&index=74)
* [Hotels.com](https://hotels.com)
* [Nanit](https://www.nanit.com/) - [blog post](https://railsadventures.wordpress.com/2015/12/06/why-we-chose-kubernetes-over-ecs/)
* [Reddit](https://www.reddit.com/)

## Contact

This is an initiative of [SIG-AWS](https://github.com/kubernetes/community/tree/master/sig-aws).
Please create GitHub issues for questions/concerns with this repo or [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform).

Please fill out [the Google form](https://docs.google.com/a/zalando.de/forms/d/e/1FAIpQLScrZkcCP8lfAuxZcWOzEmAIP0XCO5PtnfJbU0lFLx8D2-EdNg/viewform) to add your organization instead of opening a PR.

You can also [reach the maintainer on Twitter](https://twitter.com/try_except_).
