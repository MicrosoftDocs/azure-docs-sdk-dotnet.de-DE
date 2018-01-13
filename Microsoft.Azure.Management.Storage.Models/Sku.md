<Type Name="Sku" FullName="Microsoft.Azure.Management.Storage.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
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
            Die SKU des Speicherkontos.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Sku-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.Storage.Models.SkuName name, Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier = null, string resourceType = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Models.SkuName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier, string resourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor(Microsoft.Azure.Management.Storage.Models.SkuName,System.Nullable{Microsoft.Azure.Management.Storage.Models.SkuTier},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.SKUCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.Restriction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName, Optional tier As Nullable(Of SkuTier) = null, Optional resourceType As String = null, Optional kind As Nullable(Of Kind) = null, Optional locations As IList(Of String) = null, Optional capabilities As IList(Of SKUCapability) = null, Optional restrictions As IList(Of Restriction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Sku : Microsoft.Azure.Management.Storage.Models.SkuName * Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; -&gt; Microsoft.Azure.Management.Storage.Models.Sku" Usage="new Microsoft.Azure.Management.Storage.Models.Sku (name, tier, resourceType, kind, locations, capabilities, restrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Storage.Models.SkuName" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" />
        <Parameter Name="restrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Ruft ab oder legt den Sku-Namen. Für die kontoerstellung erforderlich; Dies ist optional für das Update. Beachten Sie, dass in früheren Versionen können Sku-Name AccountType aufgerufen wurde. Folgende Werte sind möglich: "Standard_LRS", "Standard_GRS", "Standard_RAGRS", "standard_zrs" "", "premium_lrs" ""</param>
        <param name="tier">Ruft die Sku-Tarif. Dies basiert auf der SKU-Name. Folgende Werte sind möglich: "Standard", "Premium"</param>
        <param name="resourceType">Der Typ der Ressource, in der Regel ist "storageaccounts werden".</param>
        <param name="kind">Gibt den Typ des Speicherkontos. Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</param>
        <param name="locations">Der Satz von Speicherorten, dass die SKU verfügbar ist. Dies wird unterstützt und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</param>
        <param name="capabilities">Informationen über die Funktionen in der angegebenen Sku, einschließlich Verschlüsselung, Netzwerk-Acls, die Benachrichtigung.</param>
        <param name="restrictions">Die Einschränkungen aufgrund, die SKU verwendet werden kann. Dies ist leer, wenn es keine Einschränkungen gibt.</param>
        <summary>
            Initialisiert eine neue Instanz der Sku-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As IList(Of SKUCapability)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Informationen über die Funktionen in der angegebenen Sku, einschließlich Verschlüsselung, Netzwerk-Acls, die Benachrichtigung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft gibt den Typ des Speicherkontos. Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Gruppe von Standorten, dass die SKU verfügbar ist. Dies wird unterstützt und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Sku-Namen. Für die kontoerstellung erforderlich; Dies ist optional für das Update. Beachten Sie, dass in früheren Versionen können Sku-Name AccountType aufgerufen wurde. Folgende Werte sind möglich: "Standard_LRS", "Standard_GRS", "Standard_RAGRS", "standard_zrs" "", "premium_lrs" ""
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ der Ressource, in der Regel, die es ist "storageaccounts werden" ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property Restrictions As IList(Of Restriction)" />
      <MemberSignature Language="F#" Value="member this.Restrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="restrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen / definieren die Einschränkungen, die aufgrund, die SKU verwendet werden kann.
            Dies ist leer, wenn es keine Einschränkungen gibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As Nullable(Of SkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sku-Tarif. Dies basiert auf der SKU-Name. Folgende Werte sind möglich: "Standard", "Premium"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>