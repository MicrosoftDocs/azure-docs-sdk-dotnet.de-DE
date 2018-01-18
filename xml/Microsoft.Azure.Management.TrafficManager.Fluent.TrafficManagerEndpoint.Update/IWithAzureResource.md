<Type Name="IWithAzureResource" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithAzureResource">
  <TypeSignature Language="C#" Value="public interface IWithAzureResource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAzureResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithAzureResource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAzureResource" />
  <TypeSignature Language="F#" Value="type IWithAzureResource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="02a77-101">Die Phase einer Azure-Endpunkt Update ermöglichen das Ziel Azure-Ressource an.</span><span class="sxs-lookup"><span data-stu-id="02a77-101">The stage of an Azure endpoint update allowing to specify the target Azure resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToResourceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate ToResourceId (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate ToResourceId(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithAzureResource.ToResourceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToResourceId (resourceId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToResourceId : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithAzureResource.ToResourceId resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="02a77-102">Die Id des Azure-Ressource.</span><span class="sxs-lookup"><span data-stu-id="02a77-102">The Azure resource id.</span></span></param>
        <summary>
            <span data-ttu-id="02a77-103">Gibt die Ressourcen-ID des Azure-Ressource an.</span><span class="sxs-lookup"><span data-stu-id="02a77-103">Specifies the resource ID of an Azure resource.</span></span>
            <span data-ttu-id="02a77-104">Unterstützte Azure-Ressourcen sind Cloud-Dienst, WebApp oder die öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="02a77-104">supported Azure resources are cloud service, web app or public ip.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="02a77-105">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="02a77-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>