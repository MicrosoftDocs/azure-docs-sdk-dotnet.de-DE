<Type Name="KeyCredential" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential">
  <TypeSignature Language="C#" Value="public class KeyCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyCredential" />
  <TypeSignature Language="F#" Value="type KeyCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20820-101">Informationen zur Active Directory-Schlüssel-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="20820-101">Active Directory Key Credential information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="20820-102">Initialisiert eine neue Instanz der KeyCredential-Klasse.</span><span class="sxs-lookup"><span data-stu-id="20820-102">Initializes a new instance of the KeyCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyCredential (string customKeyIdentifier = null, Nullable&lt;DateTime&gt; startDate = null, Nullable&lt;DateTime&gt; endDate = null, string value = null, string keyId = null, string usage = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string customKeyIdentifier, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endDate, string value, string keyId, string usage, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.#ctor(System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional customKeyIdentifier As String = null, Optional startDate As Nullable(Of DateTime) = null, Optional endDate As Nullable(Of DateTime) = null, Optional value As String = null, Optional keyId As String = null, Optional usage As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential : string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential" Usage="new Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential (customKeyIdentifier, startDate, endDate, value, keyId, usage, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="customKeyIdentifier" Type="System.String" />
        <Parameter Name="startDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="keyId" Type="System.String" />
        <Parameter Name="usage" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="customKeyIdentifier">To be added.</param>
        <param name="startDate">To be added.</param>
        <param name="endDate">To be added.</param>
        <param name="value">To be added.</param>
        <param name="keyId">To be added.</param>
        <param name="usage">To be added.</param>
        <param name="type">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomKeyIdentifier">
      <MemberSignature Language="C#" Value="public string CustomKeyIdentifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CustomKeyIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.CustomKeyIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomKeyIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.CustomKeyIdentifier : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.CustomKeyIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="customKeyIdentifier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.EndDate" />
      <MemberSignature Language="VB.NET" Value="Public Property EndDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.EndDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20820-103">Ruft ab, oder legt ihn fest Enddatum.</span><span class="sxs-lookup"><span data-stu-id="20820-103">Gets or sets end date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyId">
      <MemberSignature Language="C#" Value="public string KeyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.KeyId" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyId As String" />
      <MemberSignature Language="F#" Value="member this.KeyId : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.KeyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20820-104">Ruft ab oder legt Schlüssel-ID.</span><span class="sxs-lookup"><span data-stu-id="20820-104">Gets or sets key ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.StartDate" />
      <MemberSignature Language="VB.NET" Value="Public Property StartDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.StartDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20820-105">Ruft ab, oder legt ihn fest Startdatum.</span><span class="sxs-lookup"><span data-stu-id="20820-105">Gets or sets start date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="20820-106">Ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="20820-106">Gets or sets type.</span></span> <span data-ttu-id="20820-107">Zulässige Werte sind "AsymmetricX509Cert" und "Symmetric".</span><span class="sxs-lookup"><span data-stu-id="20820-107">Acceptable values are 'AsymmetricX509Cert' and 'Symmetric'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usage">
      <MemberSignature Language="C#" Value="public string Usage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Usage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Usage" />
      <MemberSignature Language="VB.NET" Value="Public Property Usage As String" />
      <MemberSignature Language="F#" Value="member this.Usage : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Usage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20820-108">Ruft ab oder legt Verwendung fest.</span><span class="sxs-lookup"><span data-stu-id="20820-108">Gets or sets usage.</span></span> <span data-ttu-id="20820-109">Zulässige Werte sind "Überprüfen" und "Anmelden".</span><span class="sxs-lookup"><span data-stu-id="20820-109">Acceptable values are 'Verify' and 'Sign'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="20820-110">Ruft ab oder legt die Schlüssel-Wert.</span><span class="sxs-lookup"><span data-stu-id="20820-110">Gets or sets key value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>