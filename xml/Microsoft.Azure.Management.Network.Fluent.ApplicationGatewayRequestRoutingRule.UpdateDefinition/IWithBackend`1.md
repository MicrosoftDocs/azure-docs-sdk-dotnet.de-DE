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
    <typeparam name="ParentT"><span data-ttu-id="ab77f-101">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="ab77f-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="ab77f-102">Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition ermöglicht an das Back-End, um die Weiterleitungsregel mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="ab77f-102">The stage of an application gateway request routing rule definition allowing to specify the backend to associate the routing rule with.</span></span>
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
        <param name="name"><span data-ttu-id="ab77f-103">Der Name der ein vorhandenes Back-End.</span><span class="sxs-lookup"><span data-stu-id="ab77f-103">The name of an existing backend.</span></span></param>
        <summary>
            <span data-ttu-id="ab77f-104">Ordnet die Weiterleitungsregel Anfrage ein Back-End auf diese Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="ab77f-104">Associates the request routing rule with a backend on this application gateway.</span></span>
            <span data-ttu-id="ab77f-105">Wenn der Back-End-noch nicht vorhanden ist, muss es in den optionalen Teil der Gateway Anwendungsdefinition mit defineBackend(...) definiert werden. Die Weiterleitungsregel Anfrage verweist er nur anhand des Namens auf.</span><span class="sxs-lookup"><span data-stu-id="ab77f-105">If the backend does not yet exist, it must be defined in the optional part of the application gateway definition, using  defineBackend(...). The request routing rule references it only by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ab77f-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="ab77f-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>