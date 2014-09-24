## Custom Setups of AWS AMIs

### CentOS 6 HVM

This is the procedure I am using to create a CentOS 6 HVM AMI on AWS.
To bootstrap it, I used the CentOS 6 AMI the core developers have setup some in the
[AWS MarketPlace](https://aws.amazon.com/marketplace/seller-profile?id=16cb8b03-256e-4dde-8f34-1b0f377efe89).
This does not have the enhanced networking drivers configured as it is not
part of mainline CentOS6.

### CentOS 5

This is the procedure I am using to create a CentOS 5 AMI on AWS. If you want
a CentOS 6 AMI, the core developers have setup some in the
[AWS MarketPlace](https://aws.amazon.com/marketplace/seller-profile?id=16cb8b03-256e-4dde-8f34-1b0f377efe89).
However, I needed a CentOS 5 install for a client and this was the cleanest
way to produce an AMI without dragging along all the extras from one of the
community-provided AMI.

### Mageia2

These 3 docs are duplicates of the posts I wrote up on
[my blog](http://blog.tonns.org/2012/11/mageia2-on-ec2-flying-in-different.html).
They are not as clean as the CentOS setup, but have workable directions on
how to get the instance store AMI, kernel compile and EBS AMI setup.

### License

Copyright 2013 Corsis
http://www.corsis.com/

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

