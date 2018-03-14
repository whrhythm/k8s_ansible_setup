# k8s_ansible_setup

这里有一个节点，两个节点，三个节点的基于http的简单部署。

部署过程如下：
比如一个节点的
cd kubernetes_ansible_1_node
假设需要部署的物理机IP为10.99.3.100(master),10.99.3.101(node)
编译hosts里面的ip，ip设置为需要的ip。

然后在本机上面安在ansible-playbook工具

执行ansible-playbook -i hosts k8s_1_config.yml
