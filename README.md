# Formacao-Kubernetes-DIO

<h4>Arquivo de configuracao do Kubernetes</h4>
<p>
  No windows dentro do diretorio <emph>Users\usuario\.kube</emph> existe o arquivo config. Neste arquivo é usado o comando para trazer as configuracoes do cluster EKS diretamente da nuvem. <strong> eks --region sa-east-1 update-kubeconfig --name kubernetes-lab</strong>
</p>

<h4>Comandos</h4>
<ul>
  <li><strong>kubectl get svc</strong> === mostra o status do cluster Kubernetes setado no arquivo config.</li>
   <li><strong>kubectl get nodes --watch</strong> === verifica se os <emph>nos</emph> estao subindo.</li>
</ul>
