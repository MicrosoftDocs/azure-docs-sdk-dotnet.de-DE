<Type Name="ApplePushMessage" FullName="Microsoft.Azure.Mobile.Server.ApplePushMessage">
  <TypeSignature Language="C#" Value="public class ApplePushMessage : System.Collections.Generic.Dictionary&lt;string,object&gt;, Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ApplePushMessage extends System.Collections.Generic.Dictionary`2&lt;string, object&gt; implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplePushMessage&#xA;Inherits Dictionary(Of String, Object)&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type ApplePushMessage = class&#xA;    inherit Dictionary&lt;string, obj&gt;&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.Object&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Object</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2240:ImplementISerializableCorrectly", Justification="Expiration is not intended for serialization")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This describes a message.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7c811-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> hilft, generieren ein Apple Push Notification Service Zielgruppenadressierung benachrichtigungsnutzlast.</span><span class="sxs-lookup"><span data-stu-id="7c811-101">The <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> helps generating a notification payload targeting Apple Push Notification Service.</span></span> <span data-ttu-id="7c811-102">Benachrichtigungen können gesendet werden, mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="7c811-102">Notifications can be sent using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplePushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c811-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Klasse erstellen eine Benachrichtigung für Apple Push Notification Service ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="7c811-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> class enabling creation a notification message targeting Apple Push Notification Service.</span></span> <span data-ttu-id="7c811-104">Legen Sie die entsprechenden Eigenschaften für die Nachricht, und senden Sie über die <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span><span class="sxs-lookup"><span data-stu-id="7c811-104">Set the appropriate properties on the message and submit through the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ApplePushMessage (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApplePushMessage : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.ApplePushMessage" Usage="new Microsoft.Azure.Mobile.Server.ApplePushMessage (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="7c811-105">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="7c811-105">A <see cref="T:System.Runtime.Serialization.SerializationInfo" /> containing information about the <see cref="T:Microsoft.Azure.Mobile.Server.AlertProperties" /> to be initialized.</span></span></param>
        <param name="context"><span data-ttu-id="7c811-106">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</span><span class="sxs-lookup"><span data-stu-id="7c811-106">A <see cref="T:System.Runtime.Serialization.StreamingContext" /> that indicates the source destination and context information of a serialized stream.</span></span></param>
        <summary>
            <span data-ttu-id="7c811-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="7c811-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> class with the specified serialization information and streaming context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplePushMessage (string alert, Nullable&lt;TimeSpan&gt; expiration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string alert, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; expiration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.#ctor(System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (alert As String, expiration As Nullable(Of TimeSpan))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApplePushMessage : string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Mobile.Server.ApplePushMessage" Usage="new Microsoft.Azure.Mobile.Server.ApplePushMessage (alert, expiration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="alert" Type="System.String" />
        <Parameter Name="expiration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="alert"><span data-ttu-id="7c811-108">Benachrichtigung Warnmeldung an.</span><span class="sxs-lookup"><span data-stu-id="7c811-108">The notification alert message.</span></span></param>
        <param name="expiration"><span data-ttu-id="7c811-109">Ein <see cref="T:System.TimeSpan" /> relativ zum aktuellen Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="7c811-109">A <see cref="T:System.TimeSpan" /> relative to the current time.</span></span> <span data-ttu-id="7c811-110">Am Ende der Lebensdauer der Benachrichtigung ist nicht mehr gültig und kann verworfen werden.</span><span class="sxs-lookup"><span data-stu-id="7c811-110">At the end of the lifetime, the notification is no longer valid and can be discarded.</span></span> <span data-ttu-id="7c811-111">Wenn dieser Wert ungleich Null ist, wird APNs speichert die Benachrichtigung und mindestens einmal die Benachrichtigung zu übermitteln versucht.</span><span class="sxs-lookup"><span data-stu-id="7c811-111">If this value is non-null, APNs stores the notification and tries to deliver the notification at least once.</span></span> <span data-ttu-id="7c811-112">Geben Sie Null an, um anzugeben, dass die Benachrichtigung sofort abläuft und APNs die Benachrichtigung nicht überhaupt speichern soll.</span><span class="sxs-lookup"><span data-stu-id="7c811-112">Specify null to indicate that the notification expires immediately and that APNs should not store the notification at all.</span></span></param>
        <summary>
            <span data-ttu-id="7c811-113">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> -Klasse mit einer angegebenen <paramref name="alert" /> Nachricht und eine optionale <paramref name="expiration" /> der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="7c811-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> class with a given <paramref name="alert" /> message and an optional <paramref name="expiration" /> of the notification.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Aps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.ApsProperties Aps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.ApsProperties Aps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.Aps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Aps As ApsProperties" />
      <MemberSignature Language="F#" Value="member this.Aps : Microsoft.Azure.Mobile.Server.ApsProperties" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.Aps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.ApsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c811-114">Ruft den <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> für diesen <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> ab.</span><span class="sxs-lookup"><span data-stu-id="7c811-114">Gets the <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> for this <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; Expiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; Expiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.Expiration" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiration As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.Expiration : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.Expiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c811-115">Ruft die Lebensdauer der Benachrichtigung ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="7c811-115">Sets or gets the lifetime of the notification.</span></span> <span data-ttu-id="7c811-116">Am Ende der Lebensdauer der Benachrichtigung ist nicht mehr gültig und kann verworfen werden.</span><span class="sxs-lookup"><span data-stu-id="7c811-116">At the end of the lifetime, the notification is no longer valid and can be discarded.</span></span> <span data-ttu-id="7c811-117">Wenn dieser Wert ungleich Null ist, wird APNs speichert die Benachrichtigung und mindestens einmal die Benachrichtigung zu übermitteln versucht.</span><span class="sxs-lookup"><span data-stu-id="7c811-117">If this value is non-null, APNs stores the notification and tries to deliver the notification at least once.</span></span> <span data-ttu-id="7c811-118">Geben Sie Null an, um anzugeben, dass die Benachrichtigung sofort abläuft und APNs die Benachrichtigung nicht überhaupt speichern soll.</span><span class="sxs-lookup"><span data-stu-id="7c811-118">Specify null to indicate that the notification expires immediately and that APNs should not store the notification at all.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPayload">
      <MemberSignature Language="C#" Value="public string JsonPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JsonPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApplePushMessage.JsonPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPayload As String" />
      <MemberSignature Language="F#" Value="member this.JsonPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApplePushMessage.JsonPayload" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c811-119">Als Alternative zum Erstellen der benachrichtigungs durch die Initialisierung der <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> direkt, es ist möglich, eine vollständige JSON-Darstellung bereitgestellt werden, die auf den Notification Hub unverändert gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="7c811-119">As an alternative to building the notification by initializing the <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> directly, it is possible to provide a complete JSON representation which will be sent to the Notification Hub unaltered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApplePushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applePushMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c811-120">Bietet eine JSON-codierten Darstellung dieses<see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /></span><span class="sxs-lookup"><span data-stu-id="7c811-120">Provides a JSON encoded representation of this <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /></span></span></summary>
        <returns><span data-ttu-id="7c811-121">Eine JSON-codierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="7c811-121">A JSON encoded string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>