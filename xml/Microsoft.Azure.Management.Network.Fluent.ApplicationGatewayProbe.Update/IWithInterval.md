<Type Name="IWithInterval" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval">
  <TypeSignature Language="C#" Value="public interface IWithInterval" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInterval" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInterval" />
  <TypeSignature Language="F#" Value="type IWithInterval = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a3f78-101">Die Phase einer Anwendung Gateway Prüfpunkt Update Möglichkeit zum Angeben des Zeitintervalls zwischen aufeinander folgenden Prüfpunkte.</span><span class="sxs-lookup"><span data-stu-id="a3f78-101">Stage of an application gateway probe update allowing to specify the time interval between consecutive probes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeBetweenProbesInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeBetweenProbesInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeBetweenProbesInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval.WithTimeBetweenProbesInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeBetweenProbesInSeconds (seconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTimeBetweenProbesInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithInterval.WithTimeBetweenProbesInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds"><span data-ttu-id="a3f78-102">Eine Zahl zwischen 1 und 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="a3f78-102">A number of seconds between 1 and 86400.</span></span></param>
        <summary>
            <span data-ttu-id="a3f78-103">Gibt das Zeitintervall in Sekunden zwischen aufeinanderfolgenden Prüfpunkte an.</span><span class="sxs-lookup"><span data-stu-id="a3f78-103">Specifies the time interval in seconds between consecutive probes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a3f78-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a3f78-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>