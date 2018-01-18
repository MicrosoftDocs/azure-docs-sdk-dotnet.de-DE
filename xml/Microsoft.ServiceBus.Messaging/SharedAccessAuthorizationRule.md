<Type Name="SharedAccessAuthorizationRule" FullName="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRule : Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRule extends Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRule&#xA;Inherits AuthorizationRule" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRule = class&#xA;    inherit AuthorizationRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.AuthorizationRule</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SharedAccessAuthorizationRule", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="be020-101">Definiert die Autorisierungsregel für gemeinsamen Zugriff-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="be020-101">Defines the authorization rule for shared access operation.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="be020-102">Die Autorisierung Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="be020-102">The authorization rule key name.</span></span></param>
        <param name="rights"><span data-ttu-id="be020-103">Die Liste der Rechte.</span><span class="sxs-lookup"><span data-stu-id="be020-103">The list of rights.</span></span></param>
        <summary><span data-ttu-id="be020-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be020-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="be020-105">Die Autorisierung Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="be020-105">The authorization rule key name.</span></span></param>
        <param name="primaryKey"><span data-ttu-id="be020-106">Der Primärschlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-106">The primary key for the authorization rule.</span></span></param>
        <param name="rights"><span data-ttu-id="be020-107">Die Liste der Rechte.</span><span class="sxs-lookup"><span data-stu-id="be020-107">The list of rights.</span></span></param>
        <summary><span data-ttu-id="be020-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be020-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, string secondaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, string secondaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, secondaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, secondaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="be020-109">Die Autorisierung Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="be020-109">The authorization rule key name.</span></span></param>
        <param name="primaryKey"><span data-ttu-id="be020-110">Der Primärschlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-110">The primary key for the authorization rule.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="be020-111">Der Sekundärschlüssel für Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-111">The secondary key for the authorization rule.</span></span></param>
        <param name="rights"><span data-ttu-id="be020-112">Die Liste der Rechte.</span><span class="sxs-lookup"><span data-stu-id="be020-112">The list of rights.</span></span></param>
        <summary><span data-ttu-id="be020-113">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be020-113">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="sharedAccessAuthorizationRule.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="be020-114">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="be020-114">The object to compare with the current object.</span></span></param>
        <summary><span data-ttu-id="be020-115">Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="be020-115">Determines whether the specified object is equal to the current object.</span></span></summary>
        <returns><span data-ttu-id="be020-116">True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="be020-116">true if the specified object is equal to the current object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateRandomKey">
      <MemberSignature Language="C#" Value="public static string GenerateRandomKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateRandomKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateRandomKey () As String" />
      <MemberSignature Language="F#" Value="static member GenerateRandomKey : unit -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="be020-117">Generiert den zufälligen Schlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-117">Generates the random key for the authorization rule.</span></span></summary>
        <returns><span data-ttu-id="be020-118">Der zufällige Schlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-118">The random key for the authorization rule.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="sharedAccessAuthorizationRule.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="be020-119">Gibt den Hashcode für diese Instanz zurück.</span><span class="sxs-lookup"><span data-stu-id="be020-119">Returns the hash code for this instance.</span></span></summary>
        <returns><span data-ttu-id="be020-120">Der Hashcode für diese Instanz.</span><span class="sxs-lookup"><span data-stu-id="be020-120">The hash code for this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public override sealed string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be020-121">Ruft ab oder legt den Schlüsselnamen für die Autorisierung Regel.</span><span class="sxs-lookup"><span data-stu-id="be020-121">Gets or sets the authorization rule key name.</span></span></summary>
        <value><span data-ttu-id="be020-122">Die Autorisierung Key Regelname.</span><span class="sxs-lookup"><span data-stu-id="be020-122">The authorization rule key name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.OnValidate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate ()" />
      <MemberSignature Language="F#" Value="override this.OnValidate : unit -&gt; unit" Usage="sharedAccessAuthorizationRule.OnValidate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="be020-123">Überprüft die Gültigkeit der Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-123">Checks the validity of the authorization rule.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be020-124">Ruft ab oder legt den Primärschlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-124">Gets or sets the primary key for the authorization rule.</span></span></summary>
        <value><span data-ttu-id="be020-125">Der Primärschlüssel für die Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-125">The primary key for the authorization rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be020-126">Ruft ab oder legt den Sekundärschlüssel für Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-126">Gets or sets the secondary key for the authorization rule.</span></span></summary>
        <value><span data-ttu-id="be020-127">Der Sekundärschlüssel für Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="be020-127">The secondary key for the authorization rule.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be020-128">Ein Serialisierungsprogramm für Objekte vom Typ SharedAccessAuthorizationRule.</span><span class="sxs-lookup"><span data-stu-id="be020-128">A serializer for objects of type SharedAccessAuthorizationRule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateRights">
      <MemberSignature Language="C#" Value="protected override void ValidateRights (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; value);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ValidateRights(class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.ValidateRights(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ValidateRights (value As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="override this.ValidateRights : seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; unit" Usage="sharedAccessAuthorizationRule.ValidateRights value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="be020-129">Die Zugriffsrechte, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="be020-129">The access rights to check.</span></span></param>
        <summary><span data-ttu-id="be020-130">Überprüft die Gültigkeit der angegebenen Zugriffsrechte.</span><span class="sxs-lookup"><span data-stu-id="be020-130">Checks the validity of the specified access rights.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>