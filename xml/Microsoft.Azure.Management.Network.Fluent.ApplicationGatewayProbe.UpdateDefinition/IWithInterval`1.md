<Type Name="IWithInterval&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithInterval&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInterval`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInterval(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithInterval&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="2877c-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="2877c-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="2877c-102">Die Phase einer Anwendung Gateway Prüfpunkt Definition Möglichkeit zum Angeben des Zeitintervalls zwischen aufeinander folgenden Prüfpunkte.</span><span class="sxs-lookup"><span data-stu-id="2877c-102">Stage of an application gateway probe definition allowing to specify the time interval between consecutive probes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeBetweenProbesInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTimeBetweenProbesInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTimeBetweenProbesInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval`1.WithTimeBetweenProbesInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeBetweenProbesInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeBetweenProbesInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithInterval.WithTimeBetweenProbesInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="2877c-103">Eine Zahl zwischen 1 und 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="2877c-103">A number of seconds between 1 and 86400.</span></span></param>
        <summary>
            <span data-ttu-id="2877c-104">Gibt das Zeitintervall in Sekunden zwischen aufeinanderfolgenden Prüfpunkte an.</span><span class="sxs-lookup"><span data-stu-id="2877c-104">Specifies the time interval in seconds between consecutive probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2877c-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2877c-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>