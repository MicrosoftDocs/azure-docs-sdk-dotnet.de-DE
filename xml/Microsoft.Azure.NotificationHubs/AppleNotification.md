<Type Name="AppleNotification" FullName="Microsoft.Azure.NotificationHubs.AppleNotification">
  <TypeSignature Language="C#" Value="public sealed class AppleNotification : Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AppleNotification extends Microsoft.Azure.NotificationHubs.Notification" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AppleNotification" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AppleNotification&#xA;Inherits Notification" />
  <TypeSignature Language="F#" Value="type AppleNotification = class&#xA;    inherit Notification" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Notification</BaseTypeName>
  </Base>
  <Interfaces></Interfaces>
  <Docs>
    <summary><span data-ttu-id="6bba3-101">Stellt die Apple-Benachrichtigung an.</span><span class="sxs-lookup"><span data-stu-id="6bba3-101">Represents the Apple notification.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification jsonPayload" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6bba3-102">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6bba3-102">The JSON payload.</span></span></param>
        <summary><span data-ttu-id="6bba3-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bba3-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, Nullable&lt;DateTime&gt; expiry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, expiry As Nullable(Of DateTime))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, expiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="expiry" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6bba3-104">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6bba3-104">The JSON payload.</span></span></param>
        <param name="expiry"><span data-ttu-id="6bba3-105">Der Ablauf der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6bba3-105">The expiration of the notification.</span></span></param>
        <summary><span data-ttu-id="6bba3-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bba3-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6bba3-107">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6bba3-107">The JSON payload.</span></span></param>
        <param name="tag"><span data-ttu-id="6bba3-108">Die Benachrichtigung-Tag.</span><span class="sxs-lookup"><span data-stu-id="6bba3-108">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6bba3-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bba3-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppleNotification (string jsonPayload, Nullable&lt;DateTime&gt; expiry, string tag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string jsonPayload, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiry, string tag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.#ctor(System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jsonPayload As String, expiry As Nullable(Of DateTime), tag As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AppleNotification : string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.NotificationHubs.AppleNotification" Usage="new Microsoft.Azure.NotificationHubs.AppleNotification (jsonPayload, expiry, tag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This method is obsolete.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="jsonPayload" Type="System.String" />
        <Parameter Name="expiry" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="tag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jsonPayload"><span data-ttu-id="6bba3-110">Die JSON-Nutzlast.</span><span class="sxs-lookup"><span data-stu-id="6bba3-110">The JSON payload.</span></span></param>
        <param name="expiry"><span data-ttu-id="6bba3-111">Der Ablauf der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6bba3-111">The expiration of the notification.</span></span></param>
        <param name="tag"><span data-ttu-id="6bba3-112">Die Benachrichtigung-Tag.</span><span class="sxs-lookup"><span data-stu-id="6bba3-112">The notification tag.</span></span></param>
        <summary><span data-ttu-id="6bba3-113">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6bba3-113">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AppleNotification" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Expiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Expiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleNotification.Expiry" />
      <MemberSignature Language="VB.NET" Value="Public Property Expiry As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Expiry : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.AppleNotification.Expiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6bba3-114">Ruft ab oder legt sie fest, das Ablaufdatum und die Uhrzeit der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6bba3-114">Gets or sets the expiration date and time of the notification.</span></span></summary>
        <value><span data-ttu-id="6bba3-115">Das Ablaufdatum und die Uhrzeit der Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="6bba3-115">The expiration date and time of the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidateAndPopulateHeaders">
      <MemberSignature Language="C#" Value="protected override void OnValidateAndPopulateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidateAndPopulateHeaders() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AppleNotification.OnValidateAndPopulateHeaders" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidateAndPopulateHeaders ()" />
      <MemberSignature Language="F#" Value="override this.OnValidateAndPopulateHeaders : unit -&gt; unit" Usage="appleNotification.OnValidateAndPopulateHeaders " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6bba3-116">Überprüfen und füllt die Header.</span><span class="sxs-lookup"><span data-stu-id="6bba3-116">Validate and populates the headers.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformType">
      <MemberSignature Language="C#" Value="protected override string PlatformType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlatformType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AppleNotification.PlatformType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property PlatformType As String" />
      <MemberSignature Language="F#" Value="member this.PlatformType : string" Usage="Microsoft.Azure.NotificationHubs.AppleNotification.PlatformType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6bba3-117">Ruft den Typ der Plattform ab.</span><span class="sxs-lookup"><span data-stu-id="6bba3-117">Gets the type of the platform.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6bba3-118">Der Typ der Plattform.</span><span class="sxs-lookup"><span data-stu-id="6bba3-118">The type of the platform.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>