<Type Name="IWithFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend">
  <TypeSignature Language="C#" Value="public interface IWithFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend" />
  <TypeSignature Language="F#" Value="type IWithFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Listeners Front-End-Anwendung Gateway aktualisieren zulassen, um die Front-End-IP-Konfiguration zum Zuordnen des Listeners mit dem.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ordnet das Anwendungsgateway private (intern) Front-End den Listener zu.
            Wenn das private Front-End noch nicht vorhanden ist, wird Sie unter einem automatisch generierten Namen erstellt und das Anwendungsgateway Subnetz zugeordnet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate WithPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IWithFrontend.WithPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithFrontend.WithPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Das Anwendungsgateway öffentlichen (Internetverbindung) Front-End-Listeners zugeordnet.
            Wenn das öffentliche Front-End noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt und das Anwendungsgateway öffentliche IP-Adresse zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>