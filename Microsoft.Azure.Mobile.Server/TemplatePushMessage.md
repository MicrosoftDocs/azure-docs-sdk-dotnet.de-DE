<Type Name="TemplatePushMessage" FullName="Microsoft.Azure.Mobile.Server.TemplatePushMessage">
  <TypeSignature Language="C#" Value="public class TemplatePushMessage : System.Collections.Generic.Dictionary&lt;string,string&gt;, Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit TemplatePushMessage extends System.Collections.Generic.Dictionary`2&lt;string, string&gt; implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class TemplatePushMessage&#xA;Inherits Dictionary(Of String, String)&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type TemplatePushMessage = class&#xA;    inherit Dictionary&lt;string, string&gt;&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.String</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1710:IdentifiersShouldHaveCorrectSuffix", Justification="This describes a message.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="485cb-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> hilft, generieren eine benachrichtigungsnutzlast für Geräte, die mit einer vorlagenregistrierung registriert wurden.</span><span class="sxs-lookup"><span data-stu-id="485cb-101">The <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> helps generating a notification payload targeting devices that have registered with a template registration.</span></span> <span data-ttu-id="485cb-102">Eine Vorlage können das Gerät, das die Form der Benachrichtigungen angeben, die sie erhalten möchte, z. B. einen Satz von Schlüsselwörtern, die er möchte, dass den Absender zu füllen.</span><span class="sxs-lookup"><span data-stu-id="485cb-102">A template lets the device specify the shape of notifications that it wants to receive including a set of keywords which it wants the sender to fill in.</span></span> <span data-ttu-id="485cb-103">Anstelle der Absender die gesamte Benachrichtigung erstellen legt er einfach die Schlüsselwortwerte.</span><span class="sxs-lookup"><span data-stu-id="485cb-103">Instead of the sender building the entire notification, it simply sets the keyword values.</span></span> <span data-ttu-id="485cb-104">Notification Hub wird anschließend erstellen Sie eine Benachrichtigung mit der bestimmten Vorlage, die vom Gerät und die Schlüsselwörter, die vom Sender bereitgestellte registriert.</span><span class="sxs-lookup"><span data-stu-id="485cb-104">The Notification Hub will then build a notification using the particular template registered by device and the keywords provided by the sender.</span></span> <span data-ttu-id="485cb-105">Dies erleichtert zum Senden von Benachrichtigungen unabhängig von der Plattform des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="485cb-105">This makes it much easier to send notifications regardless of the platform of the receiver.</span></span> <span data-ttu-id="485cb-106">Die Schlüsselwörter von definiert die <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> Klasse kann gesendet werden, mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="485cb-106">The keywords defined by the <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> class can be sent using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TemplatePushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TemplatePushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="485cb-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="485cb-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TemplatePushMessage (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TemplatePushMessage.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TemplatePushMessage : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.TemplatePushMessage" Usage="new Microsoft.Azure.Mobile.Server.TemplatePushMessage (info, context)" />
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
        <param name="info"><span data-ttu-id="485cb-108">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="485cb-108">A <see cref="T:System.Runtime.Serialization.SerializationInfo" /> containing information about the <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> to be initialized.</span></span></param>
        <param name="context"><span data-ttu-id="485cb-109">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</span><span class="sxs-lookup"><span data-stu-id="485cb-109">A <see cref="T:System.Runtime.Serialization.StreamingContext" /> that indicates the source destination and context information of a serialized stream.</span></span></param>
        <summary>
            <span data-ttu-id="485cb-110">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="485cb-110">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> class with the specified serialization information and streaming context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>