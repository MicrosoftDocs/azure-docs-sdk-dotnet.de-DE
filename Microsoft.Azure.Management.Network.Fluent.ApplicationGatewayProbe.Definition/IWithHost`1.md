<Type Name="IWithHost&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHost&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHost&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHost`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHost`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHost(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithHost&lt;'ParentT&gt; = interface" />
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
            Phase von einer Anwendung Gateway Prüfpunkt Definition ermöglicht an den Host aus, um die Überprüfung zu senden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHost">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithPath&lt;ParentT&gt; WithHost (string host);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithPath`1&lt;!ParentT&gt; WithHost(string host) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithHost`1.WithHost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHost (host As String) As IWithPath(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHost : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithPath&lt;'ParentT&gt;" Usage="iWithHost.WithHost host" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithPath&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="host" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="host">Einen Hostnamen an.</param>
        <summary>
            Gibt den Hostnamen, um die Überprüfung zu senden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>