| <details> <summary></summary> Yes <br></details>                                                                                                                                                                                                                                                                                |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <details> <summary><span style="color: rgb(34, 34, 34);">Can Admission controllers act on requests that delete an object?</span></summary> Yes <br></details>                                                                                                                                                                   |
| <details> <summary><span style="color: rgb(34, 34, 34);">Can Admission controllers act on requests that connect (proxy) to an object?</span></summary> Yes <br></details>                                                                                                                                                       |
| <details> <summary><span style="color: rgb(34, 34, 34);">Can Admission controllers act on requests that read an object?</span></summary> No <br></details>                                                                                                                                                                      |
| <details> <summary>An admission controller module rejects a request. What happens to the request?</summary> It is immediately rejected. <br></details>                                                                                                                                                                          |
| <details> <summary>Can admission controllers set complex defaults for fields?</summary> Yes <br></details>                                                                                                                                                                                                                      |
| <details> <summary>Does the admission or validation of a request happen first?</summary> admission <br></details>                                                                                                                                                                                                               |
| <details> <summary>Can resource quotas improve security by preventing internal denial of service attacks?</summary> Yes <br></details>                                                                                                                                                                                          |
| <details> <summary>Open Policy Agent can manage your _____ controllers in order to block K8S features (like being able to run containers as root) from multiple teams.</summary> admission  <br></details>                                                                                                                      |
| <details> <summary>Is admission control's NodeRestriction enabled by default?</summary> No! <br></details>                                                                                                                                                                                                                      |
| <details> <summary>Kubernetes _____ provides a security-relevant chronological set of records documenting the sequence of activities that have affected system by individual users, administrators or other components of the system.</summary> auditing <br></details>                                                         |
| <details> <summary><span style="color: rgb(34, 34, 34);">Audit records begin their lifecycle inside the _____ Kubernetes</span><span style="color: rgb(34, 34, 34);"> component.</span></summary> <a href="https://kubernetes.io/docs/reference/command-line-tools-reference/kube-apiserver/">kube-apiserver</a> <br></details> |
| <details> <summary><span style="color: rgb(34, 34, 34);">Each request on each stage of its execution generates an audit _____, which is then pre-processed according to a certain policy and written to a backend.</span></summary> <span style="color: rgb(34, 34, 34);">event</span> <br></details>                           |
| <details> <summary>Audit logging usually _____ the memory consumption of the API server because some context required for auditing is stored for each request.</summary> increases  <br></details>                                                                                                                              |
| <details> <summary><span style="color: rgb(34, 34, 34);">Audit _____ objects define rules about what events should be recorded and what data they should include.</span></summary> <span style="color: rgb(34, 34, 34);">policy</span> <br></details>                                                                           |
| <details> <summary><span style="color: rgb(34, 34, 34);">When an event is processed, it's compared against the list of Audit Policy rules in order. The first matching rule sets the "_____" of the event.</span></summary> <span style="color: rgb(34, 34, 34);">audit level</span> <br></details>                             |
|                                                                                                                                                                                                                                                                                                                                 |
|                                                                                                                                                                                                                                                                                                                                 |
|                                                                                                                                                                                                                                                                                                                       |
