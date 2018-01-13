<Type Name="WindowsPushMessage" FullName="Microsoft.Azure.Mobile.Server.WindowsPushMessage">
  <TypeSignature Language="C#" Value="public class WindowsPushMessage : Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WindowsPushMessage extends System.Object implements class Microsoft.Azure.Mobile.Server.Notifications.IPushMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />
  <TypeSignature Language="VB.NET" Value="Public Class WindowsPushMessage&#xA;Implements IPushMessage" />
  <TypeSignature Language="F#" Value="type WindowsPushMessage = class&#xA;    interface IPushMessage" />
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
      <AttributeName>System.Xml.Serialization.XmlRoot("tile")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> hilft, generieren eine benachrichtigungsnutzlast Zielgruppenadressierung Windows Push Notification Services. Benachrichtigungen können gesendet werden, mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsPushMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsPushMessage (int version, params Microsoft.Azure.Mobile.Server.TileBinding[] bindings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 version, class Microsoft.Azure.Mobile.Server.TileBinding[] bindings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.#ctor(System.Int32,Microsoft.Azure.Mobile.Server.TileBinding[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (version As Integer, ParamArray bindings As TileBinding())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.WindowsPushMessage : int * Microsoft.Azure.Mobile.Server.TileBinding[] -&gt; Microsoft.Azure.Mobile.Server.WindowsPushMessage" Usage="new Microsoft.Azure.Mobile.Server.WindowsPushMessage (version, bindings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.Int32" />
        <Parameter Name="bindings" Type="Microsoft.Azure.Mobile.Server.TileBinding[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="version">Die Version des XML-Schemas Kachel wurde diese bestimmten Nutzlast für (z. B. entwickelt "1" oder "2").</param>
        <param name="bindings">Einen anfänglichen Satz von Bindungen für diesen <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Headers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Headers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Headers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.Headers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Headers As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Headers : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.Headers" />
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
            Zusätzliche HTTP-Header an die Windows Push Notification Services zusammen mit die Benachrichtigung gesendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.WindowsPushMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="windowsPushMessage.ToString " />
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
            Stellt eine XML-Darstellung der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Instanz.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visual">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Notifications.VisualTile Visual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Mobile.Server.Notifications.VisualTile Visual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.Visual" />
      <MemberSignature Language="VB.NET" Value="Public Property Visual As VisualTile" />
      <MemberSignature Language="F#" Value="member this.Visual : Microsoft.Azure.Mobile.Server.Notifications.VisualTile with get, set" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.Visual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("visual")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Notifications.VisualTile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" /> Element enthält mehrere untergeordnete Bindungselemente, von denen jede eine Kachel definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="XmlPayload">
      <MemberSignature Language="C#" Value="public string XmlPayload { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string XmlPayload" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.WindowsPushMessage.XmlPayload" />
      <MemberSignature Language="VB.NET" Value="Public Property XmlPayload As String" />
      <MemberSignature Language="F#" Value="member this.XmlPayload : string with get, set" Usage="Microsoft.Azure.Mobile.Server.WindowsPushMessage.XmlPayload" />
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
            Als Alternative zur Benachrichtigung programmgesteuert erstellen, durch das Hinzufügen von <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> um Instanzen der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" />, es ist möglich, eine vollständige XML-Darstellung bereitgestellt werden, die auf den Notification Hub unverändert gesendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>