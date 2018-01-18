<Type Name="ServiceBusEnvironment" FullName="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment">
  <TypeSignature Language="C#" Value="public static class ServiceBusEnvironment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceBusEnvironment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusEnvironment" />
  <TypeSignature Language="F#" Value="type ServiceBusEnvironment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="da514-101">Beschreibt die Windows Azure Service Bus-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="da514-101">Describes the Windows Azure Service Bus environment.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAccessControlUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAccessControlUri (string serviceNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAccessControlUri(string serviceNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateAccessControlUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAccessControlUri (serviceNamespace As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAccessControlUri : string -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateAccessControlUri serviceNamespace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceNamespace"><span data-ttu-id="da514-102">Die Erstellung den URI für.</span><span class="sxs-lookup"><span data-stu-id="da514-102">The  to create the URI for.</span></span></param>
        <summary><span data-ttu-id="da514-103">Erstellt eine URI-Zeichenfolge mit der Zugriffssteuerung für den angegebenen verwenden.</span><span class="sxs-lookup"><span data-stu-id="da514-103">Creates a URI string to use with access control for the specified .</span></span></summary>
        <returns><span data-ttu-id="da514-104">Gibt eine <see cref="T:System.Uri" /> , die den angegebenen URI enthält.</span><span class="sxs-lookup"><span data-stu-id="da514-104">Returns a <see cref="T:System.Uri" /> that contains the specified URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scheme"><span data-ttu-id="da514-105">Das URI-Schema.</span><span class="sxs-lookup"><span data-stu-id="da514-105">The scheme of the URI.</span></span></param>
        <param name="serviceNamespace"><span data-ttu-id="da514-106">Der Name, der von der Anwendung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="da514-106">The  name used by the application.</span></span></param>
        <param name="servicePath"><span data-ttu-id="da514-107">Der Pfad des Diensts, der im Abschnitt des Host-Name des URIS folgt.</span><span class="sxs-lookup"><span data-stu-id="da514-107">The service path that follows the host name section of the URI.</span></span></param>
        <summary><span data-ttu-id="da514-108">Erstellt die Windows Azure Service Bus-URI für eine Anwendung mit dem angegebenen Schema, Name und der Dienstpfad an.</span><span class="sxs-lookup"><span data-stu-id="da514-108">Constructs the Windows Azure Service Bus URI for an application, using the specified scheme,  name, and service path.</span></span></summary>
        <returns><span data-ttu-id="da514-109">Gibt eine <see cref="T:System.Uri" /> , die den neuen URI enthält.</span><span class="sxs-lookup"><span data-stu-id="da514-109">Returns a <see cref="T:System.Uri" /> that contains the new URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceUri">
      <MemberSignature Language="C#" Value="public static Uri CreateServiceUri (string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateServiceUri(string scheme, string serviceNamespace, string servicePath, bool suppressRelayPathPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateServiceUri (scheme As String, serviceNamespace As String, servicePath As String, suppressRelayPathPrefix As Boolean) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateServiceUri : string * string * string * bool -&gt; Uri" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.CreateServiceUri (scheme, serviceNamespace, servicePath, suppressRelayPathPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scheme" Type="System.String" />
        <Parameter Name="serviceNamespace" Type="System.String" />
        <Parameter Name="servicePath" Type="System.String" />
        <Parameter Name="suppressRelayPathPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scheme"><span data-ttu-id="da514-110">Das URI-Schema.</span><span class="sxs-lookup"><span data-stu-id="da514-110">The scheme of the URI.</span></span></param>
        <param name="serviceNamespace"><span data-ttu-id="da514-111">Der Name, der von der Anwendung verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="da514-111">The  name used by the application.</span></span></param>
        <param name="servicePath"><span data-ttu-id="da514-112">Der Pfad des Diensts, der im Abschnitt des Host-Name des URIS folgt.</span><span class="sxs-lookup"><span data-stu-id="da514-112">The service path that follows the host name section of the URI.</span></span></param>
        <param name="suppressRelayPathPrefix"><span data-ttu-id="da514-113">True, wenn der Relay-Pfadpräfix unterdrückt wird. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="da514-113">True if the relay path prefix is suppressed; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="da514-114">Erstellt die Windows Azure Service Bus-URI für eine Anwendung unter Verwendung des angegebenen Schemas, Name, Dienstpfad und Pfadpräfix weitergeleitet.</span><span class="sxs-lookup"><span data-stu-id="da514-114">Constructs the Windows Azure Service Bus URI for an application, using the specified scheme,  name, service path, and relayed path prefix.</span></span></summary>
        <returns><span data-ttu-id="da514-115">Gibt eine <see cref="T:System.Uri" /> , die den neuen URI enthält.</span><span class="sxs-lookup"><span data-stu-id="da514-115">Returns a <see cref="T:System.Uri" /> that contains the new URI.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultIdentityHostName">
      <MemberSignature Language="C#" Value="public static string DefaultIdentityHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultIdentityHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultIdentityHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultIdentityHostName : string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.DefaultIdentityHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="da514-116">Ruft den Standardhostnamen für Windows Azure Access Control Service ab.</span><span class="sxs-lookup"><span data-stu-id="da514-116">Gets the default host name for the Windows Azure Access Control Service.</span></span></summary>
        <value><span data-ttu-id="da514-117">Gibt den Standardhostnamen der Identität zurück.</span><span class="sxs-lookup"><span data-stu-id="da514-117">Returns the default identity host name.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemConnectivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.ConnectivitySettings SystemConnectivity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.NotificationHubs.ConnectivitySettings SystemConnectivity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.SystemConnectivity" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property SystemConnectivity As ConnectivitySettings" />
      <MemberSignature Language="F#" Value="member this.SystemConnectivity : Microsoft.Azure.NotificationHubs.ConnectivitySettings" Usage="Microsoft.Azure.NotificationHubs.ServiceBusEnvironment.SystemConnectivity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivitySettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="da514-118">Ruft den Singleton ab <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" /> -Instanz, die die Konnektivitätseinstellungen für TCP und HTTP basierenden Endpunkte enthält.</span><span class="sxs-lookup"><span data-stu-id="da514-118">Gets the singleton <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" /> instance that holds the connectivity settings for TCP and HTTP-based endpoints.</span></span></summary>
        <value><span data-ttu-id="da514-119">Gibt eine <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" /> , enthält die Einstellungen für die Netzwerkkonnektivität.</span><span class="sxs-lookup"><span data-stu-id="da514-119">Returns a <see cref="T:Microsoft.Azure.NotificationHubs.ConnectivitySettings" /> that contains the connectivity settings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>