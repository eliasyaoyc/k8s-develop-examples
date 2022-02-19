# Simple Operator

```bash
kubebuilder init --domain my.domain --repo my.domain/guestbook

kubebuilder create api --group webapp --version v1 --kind Guestbook

make install

make run

kubectl apply -f config/samples/

kubectl get guestbook

make uninstall
```