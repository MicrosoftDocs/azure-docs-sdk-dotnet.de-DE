<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition einer Anwendung-Gateway ermöglicht, ein Back-End hinzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithBackend.DefineBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackend (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithBackend.DefineBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein eindeutiger Name für das Back-End.</param>
        <summary>
            Beginn der Definition einer neuen Anwendung Gateway Back-End-Gateway zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Back-End-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>