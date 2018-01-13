<Type Name="IWithBackend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition ermöglicht an das Back-End, um die Weiterleitungsregel mit zuzuordnen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; ToBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ToBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend`1.ToBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackend (name As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithBackend.ToBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der ein vorhandenes Back-End.</param>
        <summary>
            Ordnet die Weiterleitungsregel Anfrage ein Back-End auf diese Anwendungsgateway.
            Wenn der Back-End-noch nicht vorhanden ist, muss es in den optionalen Teil der Gateway Anwendungsdefinition mit defineBackend(...) definiert werden. Die Weiterleitungsregel Anfrage verweist er nur anhand des Namens auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>