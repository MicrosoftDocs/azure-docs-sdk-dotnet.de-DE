<Type Name="PushSettings" FullName="Microsoft.Azure.Management.WebSites.Models.PushSettings">
  <TypeSignature Language="C#" Value="public class PushSettings : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PushSettings extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.PushSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PushSettings&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type PushSettings = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Push-Einstellungen für die App an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PushSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PushSettings (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;bool&gt; isPushEnabled = null, string tagWhitelistJson = null, string tagsRequiringAuth = null, string dynamicTagsJson = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;bool&gt; isPushEnabled, string tagWhitelistJson, string tagsRequiringAuth, string dynamicTagsJson) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.PushSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional isPushEnabled As Nullable(Of Boolean) = null, Optional tagWhitelistJson As String = null, Optional tagsRequiringAuth As String = null, Optional dynamicTagsJson As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.PushSettings : string * string * string * string * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.PushSettings" Usage="new Microsoft.Azure.Management.WebSites.Models.PushSettings (id, name, kind, type, isPushEnabled, tagWhitelistJson, tagsRequiringAuth, dynamicTagsJson)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isPushEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tagWhitelistJson" Type="System.String" />
        <Parameter Name="tagsRequiringAuth" Type="System.String" />
        <Parameter Name="dynamicTagsJson" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="isPushEnabled">Ruft ab oder legt ein Flag, das angibt, ob sich die Push-Endpunkt aktiviert ist.</param>
        <param name="tagWhitelistJson">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge, enthält eine Liste der Tags, die für die Verwendung durch den registrierungsendpunkt Push in der Zulassungsliste enthalten sind.</param>
        <param name="tagsRequiringAuth">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der Transponder, die Benutzerauthentifizierung, die in der Push-registrierungsendpunkt verwendet werden.
            Tags können alphanumerische Zeichen und die folgenden bestehen: "_", "@", "#", ".",":", "-".
            Überprüfung sollte an die PushRequestHandler ausgeführt werden.</param>
        <param name="dynamicTagsJson">Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der dynamischen Transponder, die von Benutzeransprüche in der Push-registrierungsendpunkt ausgewertet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der PushSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicTagsJson">
      <MemberSignature Language="C#" Value="public string DynamicTagsJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DynamicTagsJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicTagsJson As String" />
      <MemberSignature Language="F#" Value="member this.DynamicTagsJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.DynamicTagsJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicTagsJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der dynamischen Transponder, die von Benutzeransprüche in der Push-registrierungsendpunkt ausgewertet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPushEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPushEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPushEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsPushEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPushEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.IsPushEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isPushEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Flag, das angibt, ob sich die Push-Endpunkt aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagsRequiringAuth">
      <MemberSignature Language="C#" Value="public string TagsRequiringAuth { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagsRequiringAuth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberSignature Language="VB.NET" Value="Public Property TagsRequiringAuth As String" />
      <MemberSignature Language="F#" Value="member this.TagsRequiringAuth : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagsRequiringAuth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagsRequiringAuth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge mit einer Liste der Transponder, die Benutzerauthentifizierung, die in der Push-registrierungsendpunkt verwendet werden.
            Tags können alphanumerische Zeichen und die folgenden bestehen: "_", "@", "#", ".",":", "-".
            Überprüfung sollte an die PushRequestHandler ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagWhitelistJson">
      <MemberSignature Language="C#" Value="public string TagWhitelistJson { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TagWhitelistJson" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberSignature Language="VB.NET" Value="Public Property TagWhitelistJson As String" />
      <MemberSignature Language="F#" Value="member this.TagWhitelistJson : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.PushSettings.TagWhitelistJson" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tagWhitelistJson")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest eine JSON-Zeichenfolge, enthält eine Liste der Tags, die für die Verwendung durch den registrierungsendpunkt Push in der Zulassungsliste enthalten sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>