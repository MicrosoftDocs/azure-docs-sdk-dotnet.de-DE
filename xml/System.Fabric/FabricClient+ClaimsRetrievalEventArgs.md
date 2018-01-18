<Type Name="FabricClient+ClaimsRetrievalEventArgs" FullName="System.Fabric.FabricClient+ClaimsRetrievalEventArgs">
  <TypeSignature Language="C#" Value="public class FabricClient.ClaimsRetrievalEventArgs : EventArgs" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit FabricClient/ClaimsRetrievalEventArgs extends System.EventArgs" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClaimsRetrievalEventArgs" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricClient.ClaimsRetrievalEventArgs&#xA;Inherits EventArgs" />
  <TypeSignature Language="F#" Value="type FabricClient.ClaimsRetrievalEventArgs = class&#xA;    inherit EventArgs" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.EventArgs</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e04ba-101">Stellt die Ereignisargumente für ein Ereignis der Ansprüche token abrufen</span><span class="sxs-lookup"><span data-stu-id="e04ba-101">Represents the event arguments for a claims token retrieval event</span></span>
            </summary>
    <remarks><span data-ttu-id="e04ba-102">Optional kann die Anwendung einem Claims-Token für die Autorisierung zu bieten.</span><span class="sxs-lookup"><span data-stu-id="e04ba-102">Optionally allows the application to provide a claims token for authorization.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="AzureActiveDirectoryMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.Security.AzureActiveDirectoryMetadata AzureActiveDirectoryMetadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Security.AzureActiveDirectoryMetadata AzureActiveDirectoryMetadata" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClaimsRetrievalEventArgs.AzureActiveDirectoryMetadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AzureActiveDirectoryMetadata As AzureActiveDirectoryMetadata" />
      <MemberSignature Language="F#" Value="member this.AzureActiveDirectoryMetadata : System.Fabric.Security.AzureActiveDirectoryMetadata" Usage="System.Fabric.FabricClient.ClaimsRetrievalEventArgs.AzureActiveDirectoryMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Security.AzureActiveDirectoryMetadata</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e04ba-103">Ruft Metadaten für den Erwerb von einem Claims-Token aus Azure Active Directory erforderlich</span><span class="sxs-lookup"><span data-stu-id="e04ba-103">Gets metadata needed for acquiring a claims token from Azure Active Directory</span></span>
            </summary>
        <value><span data-ttu-id="e04ba-104">Das Metadatenobjekt.</span><span class="sxs-lookup"><span data-stu-id="e04ba-104">The metadata object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>