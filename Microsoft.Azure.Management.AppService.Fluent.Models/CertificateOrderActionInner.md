<Type Name="CertificateOrderActionInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner">
  <TypeSignature Language="C#" Value="public class CertificateOrderActionInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOrderActionInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOrderActionInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type CertificateOrderActionInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Zertifikat-Order-Aktion.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOrderActionInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CertificateOrderActionInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOrderActionInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; certificateOrderActionType = null, Nullable&lt;DateTime&gt; createdAt = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; certificateOrderActionType, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional certificateOrderActionType As Nullable(Of CertificateOrderActionType) = null, Optional createdAt As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner (location, id, name, type, tags, certificateOrderActionType, createdAt)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="certificateOrderActionType" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt;" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="certificateOrderActionType">Aktionstyp. Folgende Werte sind möglich: "CertificateIssued", "CertificateOrderCanceled", "CertificateOrderCreated", "CertificateRevoked", "DomainValidationComplete", "FraudDetected", "OrgNameChange", "OrgValidationComplete", "SanDrop", "FraudCleared", " CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unbekannt'</param>
        <param name="createdAt">Der Zeitpunkt, an dem die Aktion Zertifikat durchgeführt wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der CertificateOrderActionInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOrderActionType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; CertificateOrderActionType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; CertificateOrderActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.CertificateOrderActionType" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateOrderActionType As Nullable(Of CertificateOrderActionType)" />
      <MemberSignature Language="F#" Value="member this.CertificateOrderActionType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.CertificateOrderActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Aktionstyp. Folgende Werte sind möglich: "CertificateIssued", "CertificateOrderCanceled", "CertificateOrderCreated", "CertificateRevoked", "DomainValidationComplete", "FraudDetected", "OrgNameChange", "OrgValidationComplete", "SanDrop", "FraudCleared", " CertificateExpired', 'CertificateExpirationWarning', 'FraudDocumentationRequired', 'Unbekannt'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Zeit an, die Zertifikat-Aktion ausgeführt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>