## Helm Playground Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add allenyummy-helm-playground https://allenyummy.github.io/helm-playground

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.  You can then run `helm search repo <alias>` to see the charts.

To install the <ylapi> chart:

    helm install allenyummy-ylapi allenyummy-helm-playground/ylapi

To uninstall the chart:

    helm delete allenyummy-ylapi

## Reference

- [k8s summit 2024](https://k8s.ithome.com.tw/2024/workshop-page/3261)
- [練習一-創建您的第一個-helm-chart](https://mansunkuo.github.io/zh-tw/tech/helm/#練習一-創建您的第一個-helm-chart)
- [Slides](https://docs.google.com/presentation/d/1zE2GDQ-PjGAmFcIIOyki-v6EFtUSpEAfp1rF3bJWqEs/edit#slide=id.g2fc7c646d5d_0_17)
- [共筆](https://hackmd.io/@k8ssummit/2024/%2Fl18VcrHaSBm3VbLaZxHg5g)