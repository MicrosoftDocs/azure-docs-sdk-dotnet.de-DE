<Type Name="RecommendationRule" FullName="Microsoft.Azure.Management.WebSites.Models.RecommendationRule">
  <TypeSignature Language="C#" Value="public class RecommendationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.RecommendationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendationRule" />
  <TypeSignature Language="F#" Value="type RecommendationRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Empfehlung-Regel, die das empfehlungsmodul ausführen können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RecommendationRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendationRule (string name = null, string displayName = null, string message = null, Nullable&lt;Guid&gt; recommendationId = null, string description = null, string actionName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels = null, System.Collections.Generic.IList&lt;string&gt; tags = null, Nullable&lt;bool&gt; isDynamic = null, string extensionName = null, string bladeName = null, string forwardLink = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string message, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; recommendationId, string description, string actionName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; level, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; channels, class System.Collections.Generic.IList`1&lt;string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; isDynamic, string extensionName, string bladeName, string forwardLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.#ctor(System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.NotificationLevel},System.Nullable{Microsoft.Azure.Management.WebSites.Models.Channels},System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional message As String = null, Optional recommendationId As Nullable(Of Guid) = null, Optional description As String = null, Optional actionName As String = null, Optional level As Nullable(Of NotificationLevel) = null, Optional channels As Nullable(Of Channels) = null, Optional tags As IList(Of String) = null, Optional isDynamic As Nullable(Of Boolean) = null, Optional extensionName As String = null, Optional bladeName As String = null, Optional forwardLink As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule : string * string * string * Nullable&lt;Guid&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="new Microsoft.Azure.Management.WebSites.Models.RecommendationRule (name, displayName, message, recommendationId, description, actionName, level, channels, tags, isDynamic, extensionName, bladeName, forwardLink)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="recommendationId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="actionName" Type="System.String" />
        <Parameter Name="level" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;" />
        <Parameter Name="channels" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;" />
        <Parameter Name="tags" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isDynamic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="extensionName" Type="System.String" />
        <Parameter Name="bladeName" Type="System.String" />
        <Parameter Name="forwardLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Eindeutiger Name der Regel.</param>
        <param name="displayName">Benutzeroberfläche angezeigte Name der Regel.</param>
        <param name="message">Lokalisierte Name der Regel (geeignet für UI).</param>
        <param name="recommendationId">Empfehlung, die ID eines Objekts zugeordneten Empfehlung für die Regel gebunden, wenn vorhanden ist.
            Wenn ein solches Objekt nicht vorhanden ist, wird es festgelegt auf Null.</param>
        <param name="description">Lokalisierte detaillierte Beschreibung der Regel.</param>
        <param name="actionName">Der Name der Aktion, die von dieser Regel in der Zeichenfolge wird empfohlen.</param>
        <param name="level">Die Ebene der Auswirkungen, der angibt, wie kritisch diese Regel ist. Folgende Werte sind möglich: "Kritisch", "Warnung", "Information", "NonUrgentSuggestion"</param>
        <param name="channels">Liste der verfügbaren Kanäle, die diese Regel gilt. Folgende Werte sind möglich: "Benachrichtigung", "Api", "Email", "Webhook", "All"</param>
        <param name="tags">Ein Array von Kategorietags, die die Regel enthält.</param>
        <param name="isDynamic">"True", wenn dies eine dynamisch hinzugefügte Regel zugeordnet ist</param>
        <param name="extensionName">Name der Erweiterung zurück, wenn das Portal vorhanden ist.
            Dies gilt nur für dynamische Regel.</param>
        <param name="bladeName">Deep-Link ein Blatt im Portal.
            Dies gilt nur für dynamische Regel.</param>
        <param name="forwardLink">Link zu einem externen Dokument in der Regel zugeordneten weitergeleitet werden. Dies gilt nur für dynamische Regel.</param>
        <summary>
            Initialisiert eine neue Instanz der RecommendationRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionName">
      <MemberSignature Language="C#" Value="public string ActionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionName As String" />
      <MemberSignature Language="F#" Value="member this.ActionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ActionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Namen der Aktion, die von dieser Regel in der Zeichenfolge wird empfohlen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BladeName">
      <MemberSignature Language="C#" Value="public string BladeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BladeName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberSignature Language="VB.NET" Value="Public Property BladeName As String" />
      <MemberSignature Language="F#" Value="member this.BladeName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.BladeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bladeName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest deep-Link im Portal ein Blatt. Dies gilt nur für dynamische Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Channels">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.Channels&gt; Channels" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberSignature Language="VB.NET" Value="Public Property Channels As Nullable(Of Channels)" />
      <MemberSignature Language="F#" Value="member this.Channels : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Channels" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="channels")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.Channels&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der verfügbaren Kanäle, die diese Regel gilt.
            Folgende Werte sind möglich: "Benachrichtigung", "Api", "Email", "Webhook", "All"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokalisierte detaillierte Beschreibung der Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Benutzeroberfläche angezeigten Namen der Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionName">
      <MemberSignature Language="C#" Value="public string ExtensionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExtensionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionName As String" />
      <MemberSignature Language="F#" Value="member this.ExtensionName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ExtensionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Erweiterung zurück, wenn das Portal Name vorhanden ist. Dies gilt nur für dynamische Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardLink">
      <MemberSignature Language="C#" Value="public string ForwardLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardLink As String" />
      <MemberSignature Language="F#" Value="member this.ForwardLink : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.ForwardLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="forwardLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest vorwärts Link zu einem externen Dokument in der Regel zugeordneten. Dies gilt nur für dynamische Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDynamic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest "true", wenn dies eine dynamisch hinzugefügte Regel zugeordnet ist
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As Nullable(Of NotificationLevel)" />
      <MemberSignature Language="F#" Value="member this.Level : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.NotificationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt diesen fest auswirken, der angibt, wie kritisch mit dieser Regel wird.
            Folgende Werte sind möglich: "Kritisch", "Warnung", "Information", "NonUrgentSuggestion"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest lokalisierten Namen der Regel (geeignet für UI).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die eindeutigen Namen der Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RecommendationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RecommendationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecommendationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RecommendationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.RecommendationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Empfehlung, dass die ID eines Objekts zugeordneten Empfehlung an die Regel gebunden werden, wenn vorhanden ist.
            Wenn ein solches Objekt nicht vorhanden ist, wird es festgelegt auf Null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.RecommendationRule.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Array von Kategorietags, die die Regel enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>