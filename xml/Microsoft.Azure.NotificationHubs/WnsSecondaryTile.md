<Type Name="WnsSecondaryTile" FullName="Microsoft.Azure.NotificationHubs.WnsSecondaryTile">
  <TypeSignature Language="C#" Value="public class WnsSecondaryTile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WnsSecondaryTile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.WnsSecondaryTile" />
  <TypeSignature Language="VB.NET" Value="Public Class WnsSecondaryTile" />
  <TypeSignature Language="F#" Value="type WnsSecondaryTile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject(ItemRequired=Newtonsoft.Json.Required.Default, MemberSerialization=Newtonsoft.Json.MemberSerialization.OptOut)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7b68c-101">Stellt die sekundären WNS-Kachel</span><span class="sxs-lookup"><span data-stu-id="7b68c-101">Represents the WNS secondary tile</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsSecondaryTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.WnsSecondaryTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushChannel">
      <MemberSignature Language="C#" Value="public string PushChannel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PushChannel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsSecondaryTile.PushChannel" />
      <MemberSignature Language="VB.NET" Value="Public Property PushChannel As String" />
      <MemberSignature Language="F#" Value="member this.PushChannel : string with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsSecondaryTile.PushChannel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pushChannel", Required=Newtonsoft.Json.Required.Always)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b68c-102">Ruft ab oder legt den Push-Kanal.</span><span class="sxs-lookup"><span data-stu-id="7b68c-102">Gets or sets the push channel.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7b68c-103">Die Push-Kanal.</span><span class="sxs-lookup"><span data-stu-id="7b68c-103">The push channel.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushChannelExpired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PushChannelExpired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PushChannelExpired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsSecondaryTile.PushChannelExpired" />
      <MemberSignature Language="VB.NET" Value="Public Property PushChannelExpired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PushChannelExpired : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsSecondaryTile.PushChannelExpired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pushChannelExpired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b68c-104">Ruft ab, oder legt ihn fest Ablaufdatum für das Push-Kanal.</span><span class="sxs-lookup"><span data-stu-id="7b68c-104">Gets or sets the push channel expiration property.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7b68c-105">Die Push-Kanal-Ablauf-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="7b68c-105">The push channel expiration property.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsSecondaryTile.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsSecondaryTile.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b68c-106">Ruft ab oder legt die Tags.</span><span class="sxs-lookup"><span data-stu-id="7b68c-106">Gets or sets the tags.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7b68c-107">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="7b68c-107">The tags.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Templates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.NotificationHubs.InstallationTemplate&gt; Templates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.NotificationHubs.InstallationTemplate&gt; Templates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.WnsSecondaryTile.Templates" />
      <MemberSignature Language="VB.NET" Value="Public Property Templates As IDictionary(Of String, InstallationTemplate)" />
      <MemberSignature Language="F#" Value="member this.Templates : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.NotificationHubs.InstallationTemplate&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.WnsSecondaryTile.Templates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="templates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.NotificationHubs.InstallationTemplate&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b68c-108">Ruft ab oder legt das Wörterbuch von Vorlagen.</span><span class="sxs-lookup"><span data-stu-id="7b68c-108">Gets or sets the dictionary of Templates.</span></span>
            </summary>
        <value>
            <span data-ttu-id="7b68c-109">Das Wörterbuch von Vorlagen.</span><span class="sxs-lookup"><span data-stu-id="7b68c-109">The Dictionary of templates.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>