# k8sop
this is a demo for a simple k8s operator   
`kubebuilder_linux_amd64 init --domain=markfang.cn --repo=github.com/fangzj1991/k8sop --owner Mark.Fang`  
create API  
`kubebuilder_linux_amd64 create api --group apps --version v1 --kind Application`  
CRD generate  
`make manifest`
`make install`  
Controller  
`make run`

`make docker-build IMG=app-op:v0.1`  
`make deploy IMG=zhfangtest1991.azurecr.io/app-op`
