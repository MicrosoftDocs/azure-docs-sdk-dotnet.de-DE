<Type Name="MpnsMessage" FullName="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage">
  <TypeSignature Language="C#" Value="public abstract class MpnsMessage : System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MpnsMessage extends System.Object implements class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MpnsMessage&#xA;Implements IXmlSerializable" />
  <TypeSignature Language="F#" Value="type MpnsMessage = class&#xA;    interface IXmlSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="58ff5-101">Allgemeine Basisklasse für <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> und verknüpften Klassen.</span><span class="sxs-lookup"><span data-stu-id="58ff5-101">Common base class used by <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> and related classes.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="58ff5-102">Diese Klasse ist nicht für die direkte Verwendung vorgesehen; Es dient der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.CycleTile" />, und <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />.</span><span class="sxs-lookup"><span data-stu-id="58ff5-102">This class is not intended for direct use; it is used by <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />, <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.CycleTile" />, and <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MpnsMessage (string version, string template);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string version, string template) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (version As String, template As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage : string * string -&gt; Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" Usage="new Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage (version, template)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="template" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="58ff5-103">Optionale Version der Kachel, z. B. "2.0", oder Null.</span><span class="sxs-lookup"><span data-stu-id="58ff5-103">Optional version of the tile, e.g. "2.0", or null.</span></span></param>
        <param name="template"><span data-ttu-id="58ff5-104">Optionale Name der Vorlage, z. B. "FlipTile", oder Null.</span><span class="sxs-lookup"><span data-stu-id="58ff5-104">Optional name of the template, e.g. "FlipTile", or null.</span></span></param>
        <summary>
            <span data-ttu-id="58ff5-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" /> -Klasse mit einer angegebenen <paramref name="version" /> und<paramref name="template" /></span><span class="sxs-lookup"><span data-stu-id="58ff5-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage" /> class with a given <paramref name="version" /> and <paramref name="template" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="58ff5-106">Ruft die Eigenschaften für diese Toast oder -Kachel ab.</span><span class="sxs-lookup"><span data-stu-id="58ff5-106">Gets the properties associated with this toast or tile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.GetSchema">
      <MemberSignature Language="C#" Value="System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema System.Xml.Serialization.IXmlSerializable.GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.System#Xml#Serialization#IXmlSerializable#GetSchema" />
      <MemberSignature Language="VB.NET" Value="Function GetSchema () As XmlSchema Implements IXmlSerializable.GetSchema" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.ReadXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.System#Xml#Serialization#IXmlSerializable#ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Sub ReadXml (reader As XmlReader) Implements IXmlSerializable.ReadXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.WriteXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.System#Xml#Serialization#IXmlSerializable#WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Sub WriteXml (writer As XmlWriter) Implements IXmlSerializable.WriteXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="protected string Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Template" />
      <MemberSignature Language="VB.NET" Value="Protected Property Template As String" />
      <MemberSignature Language="F#" Value="member this.Template : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Template" />
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
            <span data-ttu-id="58ff5-107">Ruft ab oder legt den Vorlagennamen die Kachel oder den Toast, z. B. "FlipTile", oder <c>null</c> Wenn kein Vorlagenname vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="58ff5-107">Gets or sets the template name of the tile or toast, e.g. "FlipTile", or <c>null</c> if there is no template name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TileId">
      <MemberSignature Language="C#" Value="protected string TileId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TileId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.TileId" />
      <MemberSignature Language="VB.NET" Value="Protected Property TileId As String" />
      <MemberSignature Language="F#" Value="member this.TileId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.TileId" />
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
            <span data-ttu-id="58ff5-108">Ruft ab oder legt die Id der Kachel fest.</span><span class="sxs-lookup"><span data-stu-id="58ff5-108">Gets or sets the id of the tile.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="protected internal string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Version" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.MpnsMessage.Version" />
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
            <span data-ttu-id="58ff5-109">Ruft ab oder legt die Version von der Kachel oder den Toast, z. B. "2.0", oder <c>null</c> , wenn keine Version vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="58ff5-109">Gets or sets the version of the tile or toast, e.g. "2.0", or <c>null</c> if there is no version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>