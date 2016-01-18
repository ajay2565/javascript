# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure(2) do |config|

  config.vm.define :learn_java_script do |js|
    js.vm.box = "JavascriptBox"
    js.vm.box_url = "file:///D:/bento/builds/centos-7.2.virtualbox.box"
    js.vm.hostname = "learn-javascript"
    js.vm.network "forwarded_port", guest: 80, host: 7620
    js.vm.network "private_network", ip: "192.168.55.60"
	end

end
