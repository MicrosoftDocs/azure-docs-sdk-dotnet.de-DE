<Type Name="IWithPath&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithPath&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPath&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPath`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithPath`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPath(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPath&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="3610b-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="3610b-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="3610b-102">Die Phase einer Anwendung Gateway Prüfpunkt Definition zu ermöglichen, geben Sie den Pfad, um die Überprüfung zu senden.</span><span class="sxs-lookup"><span data-stu-id="3610b-102">Stage of an application gateway probe definition allowing to specify the path to send the probe to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPath">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithProtocol&lt;ParentT&gt; WithPath (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithProtocol`1&lt;!ParentT&gt; WithPath(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithPath`1.WithPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPath (path As String) As IWithProtocol(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPath : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithProtocol&lt;'ParentT&gt;" Usage="iWithPath.WithPath path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithProtocol&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="3610b-103">Ein relativer Pfad.</span><span class="sxs-lookup"><span data-stu-id="3610b-103">A relative path.</span></span></param>
        <summary>
            <span data-ttu-id="3610b-104">Gibt den relativen Pfad für den Prüfpunkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="3610b-104">Specifies the relative path for the probe to call.</span></span>
            <span data-ttu-id="3610b-105">Ein Prüfpunkt wird gesendet, um &lt;Protokoll&gt;://&lt;Host&gt;:&lt;Port&gt;&lt;Pfad&gt;.</span><span class="sxs-lookup"><span data-stu-id="3610b-105">A probe is sent to &lt;protocol&gt;://&lt;host&gt;:&lt;port&gt;&lt;path&gt;.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3610b-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3610b-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>