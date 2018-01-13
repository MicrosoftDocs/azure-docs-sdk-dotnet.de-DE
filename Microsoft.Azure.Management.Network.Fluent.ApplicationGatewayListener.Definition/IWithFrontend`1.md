<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Stufe der Gateway Front-End-Listener Anwendungsdefinition an die Front-End-IP-Konfiguration zum Zuordnen des Listeners mit dem zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt; WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1&lt;!ParentT&gt; WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ordnet das Anwendungsgateway private (intern) Front-End den Listener zu.
            Wenn das private Front-End noch nicht vorhanden ist, wird Sie unter einem automatisch generierten Namen erstellt und das Anwendungsgateway Subnetz zugeordnet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt; WithPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1&lt;!ParentT&gt; WithPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontend`1.WithPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.WithPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Das Anwendungsgateway öffentlichen (Internetverbindung) Front-End-Listeners zugeordnet.
            Wenn das öffentliche Front-End noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt und das Anwendungsgateway öffentliche IP-Adresse zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>