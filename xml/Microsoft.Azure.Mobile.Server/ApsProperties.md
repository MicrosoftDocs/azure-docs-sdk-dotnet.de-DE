<Type Name="ApsProperties" FullName="Microsoft.Azure.Mobile.Server.ApsProperties">
  <TypeSignature Language="C#" Value="public class ApsProperties : System.Collections.Generic.Dictionary&lt;string,object&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ApsProperties extends System.Collections.Generic.Dictionary`2&lt;string, object&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.ApsProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ApsProperties&#xA;Inherits Dictionary(Of String, Object)" />
  <TypeSignature Language="F#" Value="type ApsProperties = class&#xA;    inherit Dictionary&lt;string, obj&gt;" />
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
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This is a property bag.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3a3aa-101">Die Eigenschaft "Aps" enthält die Definition einer Benachrichtigung mit dem Apple Push Notification Service (APNS) abzielen.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-101">The "aps" property contains the definition of a notification targeting Apple Push Notification Service (APNS).</span></span> <span data-ttu-id="3a3aa-102">Richtet sich aus der <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-102">It is intended to be used from the <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApsProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a3aa-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ApsProperties (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.ApsProperties.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.ApsProperties : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.ApsProperties" Usage="new Microsoft.Azure.Mobile.Server.ApsProperties (info, context)" />
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
        <param name="info"><span data-ttu-id="3a3aa-104">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-104">A <see cref="T:System.Runtime.Serialization.SerializationInfo" /> containing information about the <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> to be initialized.</span></span></param>
        <param name="context"><span data-ttu-id="3a3aa-105">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-105">A <see cref="T:System.Runtime.Serialization.StreamingContext" /> that indicates the source destination and context information of a serialized stream.</span></span></param>
        <summary>
            <span data-ttu-id="3a3aa-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.ApsProperties" /> class with the specified serialization information and streaming context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alert">
      <MemberSignature Language="C#" Value="public string Alert { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Alert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
      <MemberSignature Language="VB.NET" Value="Public Property Alert As String" />
      <MemberSignature Language="F#" Value="member this.Alert : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Alert" />
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
            <span data-ttu-id="3a3aa-107">Die Warnmeldung als einzelne Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-107">The alert message as a single string.</span></span> <span data-ttu-id="3a3aa-108">Verwenden Sie für eine komplexere Warnmeldung Optionen <see cref="M:AlertProperties" />.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-108">For more complex alert message options, please use <see cref="M:AlertProperties" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.AlertProperties AlertProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlertProperties As AlertProperties" />
      <MemberSignature Language="F#" Value="member this.AlertProperties : Microsoft.Azure.Mobile.Server.AlertProperties" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.AlertProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.AlertProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3aa-109">Warnmeldung als Wörterbuch mit zusätzlichen Eigenschaften, die die Warnung z. B. Lokalisierungsinformationen, beschreibt das Bild angezeigt werden, usw. Wenn die Warnung ist, dann stellen Sie einfach eine Zeichenfolge verwenden <see cref="M:Alert" />.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-109">The alert message as a dictionary with additional properties describing the alert such as localization information, which image to display, etc. If the alert is simply a string then please use <see cref="M:Alert" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Badge">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Badge { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Badge" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberSignature Language="VB.NET" Value="Public Property Badge As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Badge : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Badge" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3aa-110">Die Anzahl als das Signal für das Anwendungssymbol angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-110">The number to display as the badge of the application icon.</span></span> <span data-ttu-id="3a3aa-111">Wenn diese Eigenschaft nicht vorhanden ist, wird das Signal nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-111">If this property is absent, the badge is not changed.</span></span> <span data-ttu-id="3a3aa-112">Um das Signal zu entfernen, wird den Wert dieser Eigenschaft auf 0 festgelegt.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-112">To remove the badge, set the value of this property to 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAvailable">
      <MemberSignature Language="C#" Value="public bool ContentAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ContentAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentAvailable As Boolean" />
      <MemberSignature Language="F#" Value="member this.ContentAvailable : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.ContentAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a3aa-113">Geben Sie diesen Schlüssel, mit dem Wert 1 fest, um anzugeben, dass der neue Inhalt verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-113">Provide this key with a value of 1 to indicate that new content is available.</span></span> <span data-ttu-id="3a3aa-114">Dies dient zur Unterstützung von Newsstand apps und Hintergrund Inhalt heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-114">This is used to support Newsstand apps and background content downloads.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sound">
      <MemberSignature Language="C#" Value="public string Sound { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sound" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
      <MemberSignature Language="VB.NET" Value="Public Property Sound As String" />
      <MemberSignature Language="F#" Value="member this.Sound : string with get, set" Usage="Microsoft.Azure.Mobile.Server.ApsProperties.Sound" />
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
            <span data-ttu-id="3a3aa-115">Der Name einer Audiodatei im Anwendungspaket.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-115">The name of a sound file in the application bundle.</span></span> <span data-ttu-id="3a3aa-116">Der Sound in dieser Datei wird als Warnung wiedergegeben.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-116">The sound in this file is played as an alert.</span></span> <span data-ttu-id="3a3aa-117">Wenn die Audiodatei nicht vorhanden, oder Standardwert als Wert angegeben ist, wird das Standardwarnsignal wiedergegeben.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-117">If the sound file doesn’t exist or default is specified as the value, the default alert sound is played.</span></span> <span data-ttu-id="3a3aa-118">Die Audiodatei muss in einem der audiodatenformate sein, die mit Systemsounds kompatibel sind.</span><span class="sxs-lookup"><span data-stu-id="3a3aa-118">The audio must be in one of the audio data formats that are compatible with system sounds;</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>