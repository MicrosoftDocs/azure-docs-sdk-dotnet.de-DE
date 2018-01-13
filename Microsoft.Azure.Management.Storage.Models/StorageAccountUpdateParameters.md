<Type Name="StorageAccountUpdateParameters" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountUpdateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountUpdateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountUpdateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountUpdateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            Die Parameter, die beim Aktualisieren der speicherkontoeigenschaften bereitgestellt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParameters (Microsoft.Azure.Management.Storage.Models.Sku sku = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Models.Identity identity = null, Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier = null, Nullable&lt;bool&gt; enableHttpsTrafficOnly = null, Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Models.Sku sku, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Models.Identity identity, class Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier, valuetype System.Nullable`1&lt;bool&gt; enableHttpsTrafficOnly, class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.#ctor(Microsoft.Azure.Management.Storage.Models.Sku,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Models.Identity,Microsoft.Azure.Management.Storage.Models.CustomDomain,Microsoft.Azure.Management.Storage.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccessTier},System.Nullable{System.Boolean},Microsoft.Azure.Management.Storage.Models.NetworkRuleSet,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters : Microsoft.Azure.Management.Storage.Models.Sku * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Models.Identity * Microsoft.Azure.Management.Storage.Models.CustomDomain * Microsoft.Azure.Management.Storage.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Storage.Models.NetworkRuleSet * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters (sku, tags, identity, customDomain, encryption, accessTier, enableHttpsTrafficOnly, networkRuleSet, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Models.Sku" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Storage.Models.Identity" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" />
        <Parameter Name="enableHttpsTrafficOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkRuleSet" Type="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
      </Parameters>
      <Docs>
        <param name="sku">Ruft ab oder legt den SKU-Namen. Beachten Sie, dass die SKU-Name kann nicht aktualisiert werden, um "standard_zrs" oder "premium_lrs", noch in einen anderen Wert Konten dieser Sku-Namen aktualisiert werden können.</param>
        <param name="tags">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben. Diese Tags können über Ressourcengruppen hinweg zum Anzeigen und Gruppieren von Ressourcen verwendet werden. Für eine Ressource kann maximal 15 Tags bereitgestellt werden. Jedes Tag muss einen Schlüssel, die nicht größer als 128 Zeichen und einen Wert in der Länge nicht länger als 256 Zeichen lang enthalten.</param>
        <param name="identity">Die Identität der Ressource.</param>
        <param name="customDomain">Benutzerdefinierte Domäne auf das Speicherkonto, das vom Benutzer zugewiesen. Der Name ist der CNAME-Quelle. Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt. Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</param>
        <param name="encryption">Stellt die Einstellungen für die Verschlüsselung für das Konto an. Die Standardeinstellung ist unverschlüsselt.</param>
        <param name="accessTier">Erforderlich für Speicherkonten, Kind = BlobStorage. Der Access-Ebene für die Abrechnung verwendet. Folgende Werte sind möglich: "Hot", "Super"</param>
        <param name="enableHttpsTrafficOnly">Https-Datenverkehr nur für Storage-Dienst ermöglicht, wenn auf "true" festgelegt.</param>
        <param name="networkRuleSet">Netzwerk-Regelsatz</param>
        <param name="kind">Optional. Gibt den Typ des Speicherkontos.
            Derzeit nur StorageV2 Wert vom Server unterstützt. Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest erforderlich, für Speicherkonten, Kind = BlobStorage. Der Access-Ebene für die Abrechnung verwendet. Folgende Werte sind möglich: "Hot", "Super"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest benutzerdefinierten Domäne auf das Speicherkonto, das vom Benutzer zugewiesen. Der Name ist der CNAME-Quelle. Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt. Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttpsTrafficOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttpsTrafficOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttpsTrafficOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.EnableHttpsTrafficOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttpsTrafficOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttpsTrafficOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.EnableHttpsTrafficOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsHttpsTrafficOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ermöglicht Https-Datenverkehr nur für Storage-Dienst auf, wenn auf "true" festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt stellt die Einstellungen für die Verschlüsselung für das Konto bereit. Die Standardeinstellung ist unverschlüsselt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Storage.Models.Identity with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Identität der Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Kind" />
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
            Ruft ab oder legt dies ist optional. Gibt den Typ des Speicherkontos.
            Derzeit nur StorageV2 Wert vom Server unterstützt. Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkRuleSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.NetworkRuleSet" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkRuleSet As NetworkRuleSet" />
      <MemberSignature Language="F#" Value="member this.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.NetworkRuleSet with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.NetworkRuleSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAcls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.NetworkRuleSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Netzwerk-Regelsatz
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den SKU-Namen. Beachten Sie, dass die SKU-Name kann nicht aktualisiert werden, um "standard_zrs" oder "premium_lrs", noch in einen anderen Wert Konten dieser Sku-Namen aktualisiert werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben.
            Diese Tags können über Ressourcengruppen hinweg zum Anzeigen und Gruppieren von Ressourcen verwendet werden. Für eine Ressource kann maximal 15 Tags bereitgestellt werden. Jedes Tag muss einen Schlüssel, die nicht größer als 128 Zeichen und einen Wert in der Länge nicht länger als 256 Zeichen lang enthalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountUpdateParameters.Validate " />
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