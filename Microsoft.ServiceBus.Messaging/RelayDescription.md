<Type Name="RelayDescription" FullName="Microsoft.ServiceBus.Messaging.RelayDescription">
  <TypeSignature Language="C#" Value="public class RelayDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RelayDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.RelayDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type RelayDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RelayDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="44f5a-101">Stellt eine Beschreibung der Relay dar.</span><span class="sxs-lookup"><span data-stu-id="44f5a-101">Represents a relay description.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayDescription (string relayPath, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string relayPath, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.RelayDescription.#ctor(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (relayPath As String, type As RelayType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.RelayDescription : string * Microsoft.ServiceBus.RelayType -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="new Microsoft.ServiceBus.Messaging.RelayDescription (relayPath, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayPath" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="relayPath"><span data-ttu-id="44f5a-102">Der Pfad des Relays.</span><span class="sxs-lookup"><span data-stu-id="44f5a-102">The path of the relay.</span></span></param>
        <param name="type"><span data-ttu-id="44f5a-103">Der Relay-Typ.</span><span class="sxs-lookup"><span data-stu-id="44f5a-103">The relay type.</span></span></param>
        <summary><span data-ttu-id="44f5a-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44f5a-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-105">Ruft das <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ab.</span><span class="sxs-lookup"><span data-stu-id="44f5a-105">Gets the <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span></span></summary>
        <value><span data-ttu-id="44f5a-106">Die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span><span class="sxs-lookup"><span data-stu-id="44f5a-106">The <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionName">
      <MemberSignature Language="C#" Value="public string CollectionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.CollectionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionName As String" />
      <MemberSignature Language="F#" Value="member this.CollectionName : string" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.CollectionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IResourceDescription.CollectionName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-107">Ruft ab oder legt den Namen der Auflistung das Relay zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="44f5a-107">Gets or sets the name of the collection associated with the relay.</span></span></summary>
        <value><span data-ttu-id="44f5a-108">Der Name der Auflistung das Relay zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="44f5a-108">The name of the collection associated with the relay.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-109">Abrufen oder Festlegen der genaue Zeitpunkt der Erstellung der Relays.</span><span class="sxs-lookup"><span data-stu-id="44f5a-109">Gets or sets the exact time the relay was created.</span></span></summary>
        <value><span data-ttu-id="44f5a-110">Der genaue Zeitpunkt, an das Relay erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="44f5a-110">The exact time the relay was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-111">Ruft ab oder legt fest, ob das Relay dynamisch ist.</span><span class="sxs-lookup"><span data-stu-id="44f5a-111">Gets or sets whether the relay is dynamic.</span></span></summary>
        <value><span data-ttu-id="44f5a-112">"true", wenn das Relay dynamisch ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="44f5a-112">true if the relay is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenerCount">
      <MemberSignature Language="C#" Value="public int ListenerCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.ListenerCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenerCount As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenerCount : int" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.ListenerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-113">Ruft ab oder legt die Anzahl der Listener für dieses Relay.</span><span class="sxs-lookup"><span data-stu-id="44f5a-113">Gets or sets the number of listeners for this relay.</span></span></summary>
        <value><span data-ttu-id="44f5a-114">Die Anzahl der Listener für dieses Relay.</span><span class="sxs-lookup"><span data-stu-id="44f5a-114">The number of listeners for this relay.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-115">Ruft ab oder legt den Pfad des Relays fest.</span><span class="sxs-lookup"><span data-stu-id="44f5a-115">Gets or sets the path of the relay.</span></span></summary>
        <value><span data-ttu-id="44f5a-116">Der Pfad des Relays.</span><span class="sxs-lookup"><span data-stu-id="44f5a-116">The path of the relay.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayType RelayType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayType RelayType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RelayType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayType As RelayType" />
      <MemberSignature Language="F#" Value="member this.RelayType : Microsoft.ServiceBus.RelayType with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RelayType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-117">Abrufen oder festlegen den Relay-Typ.</span><span class="sxs-lookup"><span data-stu-id="44f5a-117">Gets or sets the relay type.</span></span></summary>
        <value><span data-ttu-id="44f5a-118">Der Relay-Typ.</span><span class="sxs-lookup"><span data-stu-id="44f5a-118">The relay type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresClientAuthorization">
      <MemberSignature Language="C#" Value="public bool RequiresClientAuthorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresClientAuthorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RequiresClientAuthorization" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresClientAuthorization As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresClientAuthorization : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RequiresClientAuthorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-119">Ruft ab oder legt fest, ob die Clientautorisierung für dieses Relay erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="44f5a-119">Gets or sets whether client authorization is needed for this relay.</span></span></summary>
        <value><span data-ttu-id="44f5a-120">"true", wenn Clientautorisierung für dieses Relay erforderlich ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="44f5a-120">true if client authorization is needed for this relay; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresTransportSecurity">
      <MemberSignature Language="C#" Value="public bool RequiresTransportSecurity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresTransportSecurity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.RequiresTransportSecurity" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresTransportSecurity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresTransportSecurity : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.RequiresTransportSecurity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-121">Ruft ab oder legt fest, ob die transportsicherheit für diese Relay erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="44f5a-121">Gets or sets whether transport security is needed for this relay.</span></span></summary>
        <value><span data-ttu-id="44f5a-122">"true", wenn die transportsicherheit für diese Relay erforderlich ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="44f5a-122">true if transport security is needed for this relay; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-123">Ruft ab oder legt das Datum, das Relay aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="44f5a-123">Gets or sets the date when the relay was updated.</span></span></summary>
        <value><span data-ttu-id="44f5a-124">Das Datum, an das Relay aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="44f5a-124">The date when the relay was updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.RelayDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.RelayDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="44f5a-125">Ruft ab oder legt die Benutzermetadaten, die dieser Instanz zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="44f5a-125">Gets or sets the user metadata associated with this instance.</span></span></summary>
        <value><span data-ttu-id="44f5a-126">Die Benutzermetadaten, das dieser Instanz zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="44f5a-126">The user metadata associated with this instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>