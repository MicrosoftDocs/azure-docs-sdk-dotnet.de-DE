<Type Name="ManagementGroupInfo" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo">
  <TypeSignature Language="C#" Value="public class ManagementGroupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroupInfo" />
  <TypeSignature Language="F#" Value="type ManagementGroupInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Verwaltungsgruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ManagementGroupInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupInfo (string id = null, string type = null, Nullable&lt;Guid&gt; name = null, Nullable&lt;Guid&gt; tenantId = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; name, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.#ctor(System.String,System.String,System.Nullable{System.Guid},System.Nullable{System.Guid},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional type As String = null, Optional name As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo : string * string * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo (id, type, name, tenantId, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Die ID der Verwaltungsgruppe. Beispiel:
            /Providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</param>
        <param name="type">Der Typ der Ressource. Beispiel:
            /Providers/Microsoft.Management/managementGroups</param>
        <param name="name">Der Name der Verwaltungsgruppe. Beispiel:
            20000000-0000-0000-0000-000000000000</param>
        <param name="tenantId">Die AAD-Mandanten-ID der Verwaltungsgruppe zugeordnet. Beispiel: 10000000-0000-0000-0000-000000000000</param>
        <param name="displayName">Der angezeigte Name der Verwaltungsgruppe.</param>
        <summary>
            Initialisiert eine neue Instanz der ManagementGroupInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen der Verwaltungsgruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID der Verwaltungsgruppe ab. Beispiel:
            /Providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Verwaltungsgruppe ab. Beispiel:
            20000000-0000-0000-0000-000000000000
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die AAD-Mandanten-ID der Verwaltungsgruppe zugeordnet. Beispiel: 10000000-0000-0000-0000-000000000000
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            Ruft den Typ der Ressource ab. Beispiel:
            /Providers/Microsoft.Management/managementGroups
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>