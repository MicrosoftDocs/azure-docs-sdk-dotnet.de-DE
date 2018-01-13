<Type Name="IWithPrivateFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateFrontend">
  <TypeSignature Language="C#" Value="public interface IWithPrivateFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateFrontend" />
  <TypeSignature Language="F#" Value="type IWithPrivateFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition einer internen Anwendung-Gateway ermöglicht das Anwendungsgateway mit dem virtuellen Netzwerk zugänglich gemacht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithoutPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithoutPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateFrontend.WithoutPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrivateFrontend () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithPrivateFrontend.WithoutPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass keine privaten (intern) Front-End aktiviert werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPrivateFrontend.WithPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateFrontend () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithPrivateFrontend.WithPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ermöglicht es einem privaten (intern) standardmäßig Front-End im Subnetz befinden, enthält das Anwendungsgateway.
            Einem Front-End mit dem Namen "Default" wird bei Bedarf erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>