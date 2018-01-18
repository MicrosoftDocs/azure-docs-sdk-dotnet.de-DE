<Type Name="IWithFqdn" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn">
  <TypeSignature Language="C#" Value="public interface IWithFqdn" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFqdn" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFqdn" />
  <TypeSignature Language="F#" Value="type IWithFqdn = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="122fb-101">Die Phase ein externer Endpunkt Update ermöglichen um den FQDN anzugeben.</span><span class="sxs-lookup"><span data-stu-id="122fb-101">The stage of an external endpoint update allowing to specify the FQDN.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint ToFqdn (string externalFqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint ToFqdn(string externalFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithFqdn.ToFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToFqdn (externalFqdn As String) As IUpdateExternalEndpoint" />
      <MemberSignature Language="F#" Value="abstract member ToFqdn : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint" Usage="iWithFqdn.ToFqdn externalFqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.UpdateExternalEndpoint.IUpdateExternalEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="externalFqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="externalFqdn"><span data-ttu-id="122fb-102">Den externen FQDN.</span><span class="sxs-lookup"><span data-stu-id="122fb-102">The external FQDN.</span></span></param>
        <summary>
            <span data-ttu-id="122fb-103">Gibt den FQDN des ein externer Endpunkt, der nicht gehostet wird in Azure.</span><span class="sxs-lookup"><span data-stu-id="122fb-103">Specifies the FQDN of an external endpoint that is not hosted in Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="122fb-104">Die nächste Phase des Updates für den Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="122fb-104">The next stage of the endpoint update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>