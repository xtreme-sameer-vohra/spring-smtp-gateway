# Accelerator Log

## Options
```json
{
  "projectName" : "spring-smtp-gateway",
  "containerPort" : "1026",
  "servicePort" : "25",
  "workloadNamespace" : "my-apps",
  "brokerType" : "rabbitmq",
  "msgbrokerName" : "msgbroker-spring-smtp-gateway",
  "includeBuildToolWrapper" : true
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Exclude, GeneratorValidationTransform, UniquePath)
┃ ┏ engine.transformations[0] (Exclude)
┃ ┃  Info Will exclude [accelerator.yaml, accelerator.axl]
┃ ┃ Debug LICENSE didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug doc/TAPDeployment.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug icons/email.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/Tiltfile didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/Tiltfile didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/workloads.template didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┗ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┏ ┏ engine.transformations[1].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[1].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, InvokeFragment, Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[0].delegate (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml]
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug icons/email.png matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┗ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/config/workload.yaml, **/templates/workloads.template]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml matched [**/config/workload.yaml, **/templates/workloads.template] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/config/workload.yaml, **/templates/workloads.template] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [25->25, 1026->1026, msgbroker-spring-smtp-gateway->msgbroker-spring-smt...(truncated), workloads->my-apps, <profile>->rabbitmq]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/workloads.template' matched 'templates/workloads.template' with groups {g0=templates/workloads.template} and was rewritten to 'config/workloads.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[3] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[3].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to false
┃ ┃ ┃ ┃ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/catalog/catalog.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml matched [**/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml matched [**/catalog/catalog.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [**/catalog/catalog.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [name: smtp-gateway->name: spring-smtp-ga...(truncated), name: smtp-sink->name: spring-smtp-ga...(truncated), app.kubernetes.io/part-of=spring-smtp-gateway->app.kubernetes.io/pa...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[3].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(InvokeFragment, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=null, folder=null, filename=mvnw, g0=mvnw, g1=null, g2=mvnw, g3=mvnw, g4=null} and was rewritten to 'smtp-gateway/mvnw'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw.cmd' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.cmd, folder=null, filename=mvnw.cmd, g0=mvnw.cmd, g1=null, g2=mvnw.cmd, g3=mvnw.cmd, g4=.cmd} and was rewritten to 'smtp-gateway/mvnw.cmd'
┃ ┃ ┃ ┃ ┗ ┗ Debug Path '.mvn/wrapper/maven-wrapper.properties' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.properties, folder=.mvn/wrapper/, filename=maven-wrapper.properties, g0=.mvn/wrapper/maven-wrapper.properties, g1=.mvn/wrapper/, g2=maven-wrapper.properties, g3=maven-wrapper.properties, g4=.properties} and was rewritten to 'smtp-gateway/.mvn/wrapper/maven-wrapper.properties'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(InvokeFragment, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=null, folder=null, filename=mvnw, g0=mvnw, g1=null, g2=mvnw, g3=mvnw, g4=null} and was rewritten to 'smtp-sink/mvnw'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw.cmd' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.cmd, folder=null, filename=mvnw.cmd, g0=mvnw.cmd, g1=null, g2=mvnw.cmd, g3=mvnw.cmd, g4=.cmd} and was rewritten to 'smtp-sink/mvnw.cmd'
┃ ┃ ┃ ┃ ┗ ┗ Debug Path '.mvn/wrapper/maven-wrapper.properties' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.properties, folder=.mvn/wrapper/, filename=maven-wrapper.properties, g0=.mvn/wrapper/maven-wrapper.properties, g1=.mvn/wrapper/, g2=maven-wrapper.properties, g3=maven-wrapper.properties, g4=.properties} and was rewritten to 'smtp-sink/.mvn/wrapper/maven-wrapper.properties'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug icons/email.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloads.template didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/catalog/catalog.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/catalog/catalog.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/resources/bootstrap.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/resources/application.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testConfig.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalAuthorizedCIDRConfig.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalMultiAuthorizedCIDRConfig.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/resources/properties/testLocalNoAuthorizedCIDRConfig.properties didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/SmtpSinkApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/test/java/com/java/example/smtpsink/SmtpSinkApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessage.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMailMessageConverter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-sink/src/main/java/com/java/example/smtpsink/functions/SMTPMessageSink.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/boot/SmtpGatewayApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/GetMessageHeaderStream.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/MessageSizeException.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMailMessage.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SMTPMessageHandler.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SafelistedServerSocket.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStream.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedInputStreamFactory.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/server/SizeLimitedStreamCreator.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/springconfig/SMTPServerBeanConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SMTPMailMessageConverter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/streams/SmtpGatewayMessageSource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/main/java/com/java/example/smtpmq/gateway/task/SimulatedLoadTask.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_largeRecipsTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_maxSizeTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SMTPMessageHandler_sendMessageTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_authCidrTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_multiAuthCidrTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┗ Debug smtp-gateway/src/test/java/com/java/example/smtpmq/gateway/boot/SafelistedServerSocket_noauthCidrTest.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[7] (Provenance)
┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'smtp-sink/config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┗ ┗ ┗ Debug Multiple representations for path 'smtp-gateway/config/workload.yaml', will use the one appearing last 
┗ ╺ engine.transformations[2] (UniquePath)
```
