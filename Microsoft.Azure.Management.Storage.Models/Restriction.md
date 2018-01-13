<Type Name="Restriction" FullName="Microsoft.Azure.Management.Storage.Models.Restriction">
  <TypeSignature Language="C#" Value="public class Restriction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Restriction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Restriction" />
  <TypeSignature Language="VB.NET" Value="Public Class Restriction" />
  <TypeSignature Language="F#" Value="type Restriction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Einschränkung, die aufgrund, die SKU verwendet werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Restriction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Restriction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Einschränkung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Restriction (string type = null, System.Collections.Generic.IList&lt;string&gt; values = null, string reasonCode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, class System.Collections.Generic.IList`1&lt;string&gt; values, string reasonCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Restriction.#ctor(System.String,System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional values As IList(Of String) = null, Optional reasonCode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Restriction : string * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Storage.Models.Restriction" Usage="new Microsoft.Azure.Management.Storage.Models.Restriction (type, values, reasonCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="reasonCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="type">Der Typ der Einschränkungen. Ab jetzt wird nur möglicher Wert für diesen Speicherort.</param>
        <param name="values">Der Wert der Einschränkungen. Wenn Sie den Typ der Einschränkung auf Speicherort festgelegt ist. Dies wäre Speicherorte, in denen die SKU beschränkt ist.</param>
        <param name="reasonCode">Der Grund für die Einschränkung. Ab jetzt kann dies ""quotaid "" oder "NotAvailableForSubscription" sein. Kontingent-Id wird festgelegt, wenn die SKU RequiredQuotas Parameter verfügt, wie das Abonnement nicht zu diesem Kontingent gehört. Die "NotAvailableForSubscription" bezieht sich auf Kapazität auf Domänencontroller. Folgende Werte sind möglich: "quotaid" "", "NotAvailableForSubscription"</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Einschränkung an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonCode">
      <MemberSignature Language="C#" Value="public string ReasonCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.ReasonCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonCode As String" />
      <MemberSignature Language="F#" Value="member this.ReasonCode : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.ReasonCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Grund für die Einschränkung. Ab jetzt kann dies ""quotaid "" oder "NotAvailableForSubscription" sein. Kontingent-Id wird festgelegt, wenn die SKU RequiredQuotas Parameter verfügt, wie das Abonnement nicht zu diesem Kontingent gehört. Die "NotAvailableForSubscription" bezieht sich auf Kapazität auf Domänencontroller. Folgende Werte sind möglich: "quotaid" "", "NotAvailableForSubscription"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ von Einschränkungen ab. Ab jetzt wird nur möglicher Wert für diesen Speicherort.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Restriction.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Restriction.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Wert von Einschränkungen ab. Wenn Sie den Typ der Einschränkung auf Speicherort festgelegt ist. Dies wäre Speicherorte, in denen die SKU beschränkt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>