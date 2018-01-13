<Type Name="IWithIntervalInSeconds&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithIntervalInSeconds&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithIntervalInSeconds&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIntervalInSeconds`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithIntervalInSeconds`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIntervalInSeconds(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithIntervalInSeconds&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="fd752-101">Der übergeordnete Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="fd752-101">The parent resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="fd752-102">Die Phase des TCP-Prüfpunkt Definition ermöglicht das Testintervall an.</span><span class="sxs-lookup"><span data-stu-id="fd752-102">The stage of the TCP probe definition allowing to specify the probe interval.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIntervalInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;ParentT&gt; WithIntervalInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithIntervalInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithIntervalInSeconds`1.WithIntervalInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIntervalInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIntervalInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIntervalInSeconds.WithIntervalInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="fd752-103">Anzahl der Sekunden.</span><span class="sxs-lookup"><span data-stu-id="fd752-103">Number of seconds.</span></span></param>
        <summary>
            <span data-ttu-id="fd752-104">Gibt das Intervall zwischen Prüfpunkten in Sekunden an.</span><span class="sxs-lookup"><span data-stu-id="fd752-104">Specifies the interval between probes, in seconds.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="fd752-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="fd752-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>