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
            Stellt die Ereignisargumente für ein Ereignis der Ansprüche token abrufen
            </summary>
    <remarks>Optional kann die Anwendung einem Claims-Token für die Autorisierung zu bieten.</remarks>
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
            Ruft Metadaten für den Erwerb von einem Claims-Token aus Azure Active Directory erforderlich
            </summary>
        <value>Das Metadatenobjekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>