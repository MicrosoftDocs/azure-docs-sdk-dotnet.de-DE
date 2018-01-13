<Type Name="AzureActiveDirectoryMetadata" FullName="System.Fabric.Security.AzureActiveDirectoryMetadata">
  <TypeSignature Language="C#" Value="public sealed class AzureActiveDirectoryMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AzureActiveDirectoryMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Security.AzureActiveDirectoryMetadata" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AzureActiveDirectoryMetadata" />
  <TypeSignature Language="F#" Value="type AzureActiveDirectoryMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80b7c-101">Stellt die Metadaten zum Abrufen von Authentifizierungstoken aus Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="80b7c-101">Represents the metadata used to acquire authentication tokens from Azure Active Directory.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-102">Ruft einen Wert, der angibt, der Autorität für die Position, an ein Token von abrufen.</span><span class="sxs-lookup"><span data-stu-id="80b7c-102">Gets a value indicating the authority location to acquire a token from.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-103">Gibt die Berechtigungen zurück.</span><span class="sxs-lookup"><span data-stu-id="80b7c-103">Returns the authority.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientApplication">
      <MemberSignature Language="C#" Value="public string ClientApplication { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientApplication" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.ClientApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientApplication As String" />
      <MemberSignature Language="F#" Value="member this.ClientApplication : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.ClientApplication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-104">Ruft einen Wert, der angibt, der Client-ID beim Abrufen von Token für die Clusterressource für die Anwendung verwendet.</span><span class="sxs-lookup"><span data-stu-id="80b7c-104">Gets a value indicating the client ID to use when acquiring tokens for the cluster application resource.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-105">Gibt die Client-ID.</span><span class="sxs-lookup"><span data-stu-id="80b7c-105">Returns the client ID.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRedirect">
      <MemberSignature Language="C#" Value="public string ClientRedirect { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRedirect" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.ClientRedirect" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientRedirect As String" />
      <MemberSignature Language="F#" Value="member this.ClientRedirect : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.ClientRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-106">Ruft einen Wert, der angibt, der clientumleitungs-URI.</span><span class="sxs-lookup"><span data-stu-id="80b7c-106">Gets a value indicating the client redirect URI.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-107">Gibt den clientumleitungs-URI zurück.</span><span class="sxs-lookup"><span data-stu-id="80b7c-107">Returns the client redirect URI.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterApplication">
      <MemberSignature Language="C#" Value="public string ClusterApplication { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterApplication" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.ClusterApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterApplication As String" />
      <MemberSignature Language="F#" Value="member this.ClusterApplication : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.ClusterApplication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-108">Ruft einen Wert, der angibt, der Clusterressource für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="80b7c-108">Gets a value indicating the cluster application resource.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-109">Gibt die Clusterressource für die Anwendung zurück.</span><span class="sxs-lookup"><span data-stu-id="80b7c-109">Returns the cluster application resource.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginEndpoint">
      <MemberSignature Language="C#" Value="public string LoginEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginEndpoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.LoginEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoginEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.LoginEndpoint : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.LoginEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-110">Ruft einen Wert, der angibt, die Azure Active Directory-Anmeldung instanzenendpunkt (für die ADAL-Initialisierung).</span><span class="sxs-lookup"><span data-stu-id="80b7c-110">Gets a value indicating the Azure Active Directory login instance endpoint (for ADAL initialization).</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-111">Gibt die Anmelde-Endpunkt zurück.</span><span class="sxs-lookup"><span data-stu-id="80b7c-111">Returns the login instance endpoint.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Security.AzureActiveDirectoryMetadata.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="System.Fabric.Security.AzureActiveDirectoryMetadata.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80b7c-112">Ruft einen Wert, der angibt, der Mandanten-ID des entsprechenden Azure Active Directory-Mandanten an.</span><span class="sxs-lookup"><span data-stu-id="80b7c-112">Gets a value indicating the tenant ID of the relevant Azure Active Directory tenant.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80b7c-113">Gibt die Mandanten-ID zurück.</span><span class="sxs-lookup"><span data-stu-id="80b7c-113">Returns the tenant ID.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>