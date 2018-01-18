<Type Name="IWithTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTimeout&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="14ae6-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="14ae6-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="14ae6-102">Fehler bei der Phase von einer Anwendung Gateway Prüfpunkt Definition ermöglicht die Zeitspanne, nach dem Angeben der Prüfpunkts betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="14ae6-102">Stage of an application gateway probe definition allowing to specify the amount of time to after which the probe is considered failed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt; WithTimeoutInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithTimeoutInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithTimeout`1.WithTimeoutInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeoutInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeoutInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTimeout.WithTimeoutInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="14ae6-103">Eine Zahl zwischen 1 und 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="14ae6-103">A number of seconds, between 1 and 86400.</span></span></param>
        <summary>
            <span data-ttu-id="14ae6-104">Gibt die Zeitdauer in Sekunden an, das Warten auf eine Antwort, damit der Test ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="14ae6-104">Specifies the amount of time in seconds waiting for a response before the probe is considered failed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="14ae6-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="14ae6-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>