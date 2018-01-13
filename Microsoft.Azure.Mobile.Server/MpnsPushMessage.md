<Type Name="MpnsPushMessage" FullName="Microsoft.Azure.Mobile.Server.MpnsPushMessage">
  <TypeSignature Language="C#" Value="public class MpnsPushMessage : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MpnsPushMessage extends System.Object implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class MpnsPushMessage&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type MpnsPushMessage = class&#xA;    interface IPushMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Notifications.IPushMessage</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("Notification", Namespace="WPNotification")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> Klasse hilft beim Generieren einer benachrichtigungsnutzlast für Microsoft-Pushbenachrichtigungsdiensten. Benachrichtigungen können gesendet werden, mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MpnsPushMessage (Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage toastOrTile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage toastOrTile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MpnsPushMessage.#ctor(Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (toastOrTile As MpnsMessage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.MpnsPushMessage : Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage -&gt; Microsoft.Azure.Mobile.Server.MpnsPushMessage" Usage="new Microsoft.Azure.Mobile.Server.MpnsPushMessage toastOrTile" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="toastOrTile" Type="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
      </Parameters>
      <Docs>
        <param name="toastOrTile">Einer der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.CycleTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.Toast" />.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> -Klasse mit einer angegebenen <paramref name="toastOrTile" />.
            Die Toast oder -Kachel kann <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.CycleTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.Toast" /> (definiert der <c>Benachrichtigungen</c> Namespace).
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MpnsPushMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Mobile.Server.MpnsPushMessage.Headers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Zusätzliche HTTP-Header an den Microsoft-Pushbenachrichtigungsdiensten zusammen mit die Benachrichtigung gesendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MpnsPushMessage.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As MpnsMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage with get, set" Usage="Microsoft.Azure.Mobile.Server.MpnsPushMessage.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("Toast", typeof(Microsoft.Azure.Mobile.Server.Notifications.Toast))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("Tile", typeof(Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die spezifischen <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" /> für diese Instanz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MpnsPushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="mpnsPushMessage.ToString " />
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
            Stellt eine XML-Darstellung der <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> Instanz.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MpnsPushMessage.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MpnsPushMessage.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version von der der Popupbenachrichtigungen oder Kachel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="XmlPayload">
      <MemberSignature Language="C#" Value="public string XmlPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string XmlPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MpnsPushMessage.XmlPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property XmlPayload As String" />
      <MemberSignature Language="F#" Value="member this.XmlPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MpnsPushMessage.XmlPayload" />
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
            Als Alternative zum Erstellen der Benachrichtigung wird programmgesteuert über eine <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.CycleTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" /> <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />, oder <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.Toast" /> (definiert der <c>Benachrichtigungen</c> Namespace), es ist möglich, geben Sie eine vollständige XML Darstellung der auf den Notification Hub unverändert gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>