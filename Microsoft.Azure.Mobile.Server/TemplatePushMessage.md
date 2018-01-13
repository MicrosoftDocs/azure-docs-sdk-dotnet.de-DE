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
            Die <see cref="T:Microsoft.Azure.Mobile.Server.ApplePushMessage" /> hilft, generieren eine benachrichtigungsnutzlast für Geräte, die mit einer vorlagenregistrierung registriert wurden. Eine Vorlage können das Gerät, das die Form der Benachrichtigungen angeben, die sie erhalten möchte, z. B. einen Satz von Schlüsselwörtern, die er möchte, dass den Absender zu füllen. Anstelle der Absender die gesamte Benachrichtigung erstellen legt er einfach die Schlüsselwortwerte. Notification Hub wird anschließend erstellen Sie eine Benachrichtigung mit der bestimmten Vorlage, die vom Gerät und die Schlüsselwörter, die vom Sender bereitgestellte registriert. Dies erleichtert zum Senden von Benachrichtigungen unabhängig von der Plattform des Empfängers. Die Schlüsselwörter von definiert die <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> Klasse kann gesendet werden, mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> Klasse.
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />-Klasse.
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
        <param name="info">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" /> initialisiert werden.</param>
        <param name="context">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TemplatePushMessage" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>