<Type Name="IWithRetries&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRetries&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRetries`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRetries(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRetries&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="43f92-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="43f92-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="43f92-102">Phase ein Gateway Prüfpunkt Anwendungsdefinition festlegen, dass die Anzahl der Wiederholungsversuche vor dem Server angeben, wird als fehlerhaft betrachtet.</span><span class="sxs-lookup"><span data-stu-id="43f92-102">Stage of an application gateway probe definition allowing to specify the number of retries before the server is considered unhealthy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRetriesBeforeUnhealthy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt; WithRetriesBeforeUnhealthy (int retryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithRetriesBeforeUnhealthy(int32 retryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithRetries`1.WithRetriesBeforeUnhealthy(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetriesBeforeUnhealthy (retryCount As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRetriesBeforeUnhealthy : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRetries.WithRetriesBeforeUnhealthy retryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="retryCount"><span data-ttu-id="43f92-103">Eine Zahl zwischen 1 und 20 ein.</span><span class="sxs-lookup"><span data-stu-id="43f92-103">A number between 1 and 20.</span></span></param>
        <summary>
            <span data-ttu-id="43f92-104">Gibt die Anzahl der Wiederholungsversuche an, bevor der Server als fehlerhaft eingestuft wird.</span><span class="sxs-lookup"><span data-stu-id="43f92-104">Specifies the number of retries before the server is considered unhealthy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="43f92-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="43f92-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>