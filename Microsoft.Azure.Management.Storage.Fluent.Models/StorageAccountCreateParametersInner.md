<Type Name="StorageAccountCreateParametersInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParametersInner" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Die Parameter verwendet, wenn ein Speicherkonto erstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCreateParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParametersInner (Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind kind, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.Sku,Microsoft.Azure.Management.Storage.Fluent.Models.Kind,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner : Microsoft.Azure.Management.Storage.Fluent.Models.Sku * Microsoft.Azure.Management.Storage.Fluent.Models.Kind * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner (sku, kind, location, tags, customDomain, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="kind" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Kind" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="sku">Erforderlich. Ruft ab oder legt den Sku-Namen.</param>
        <param name="kind">Erforderlich. Gibt den Typ des Speicherkontos.
            Folgende Werte sind möglich: "Speicher", "BlobStorage"</param>
        <param name="location">Erforderlich. Ruft ab oder legt den Speicherort der Ressource fest. Dies ist einer der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.). Die geografische Region für eine Ressource kann nicht geändert werden, nachdem er erstellt, aber wenn Sie eine identische geografische Region für Update angegeben ist, wird die Anforderung erfolgreich.</param>
        <param name="tags">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben. Diese Tags können verwendet werden, für die Anzeige und gruppieren diese Ressource (über Ressourcengruppen hinweg). Für eine Ressource kann maximal 15 Tags bereitgestellt werden. Jedes Tag muss es sich um einen Schlüssel mit einer Länge von 128 Zeichen nicht überschreiten und einen Wert mit einer Länge von maximal 256 Zeichen verfügen.</param>
        <param name="customDomain">Die Domäne des Benutzers, dem Speicherkonto zugewiesen. Der Name ist der CNAME-Quelle. Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt. Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</param>
        <param name="encryption">Stellt die Einstellungen für die Verschlüsselung für das Konto an. Wenn die Verschlüsselung kontoeinstellungen bleibt gleich nicht angegeben. Die Standardeinstellung ist unverschlüsselt.</param>
        <param name="accessTier">Erforderlich für Speicherkonten, Kind = BlobStorage. Der Access-Ebene für die Abrechnung verwendet. Folgende Werte sind möglich: "Hot", "Super"</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCreateParametersInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Domäne des Benutzers mit dem Speicherkonto zugewiesen. Der Name ist der CNAME-Quelle. Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt. Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt stellt die Einstellungen für die Verschlüsselung für das Konto bereit. Wenn die Verschlüsselung kontoeinstellungen bleibt gleich nicht angegeben. Die Standardeinstellung ist unverschlüsselt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Fluent.Models.Kind with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt erforderlich. Gibt den Typ des Speicherkontos.
            Folgende Werte sind möglich: "Speicher", "BlobStorage"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt erforderlich. Ruft ab oder legt den Speicherort der Ressource fest.
            Dies ist einer der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.). Die geografische Region für eine Ressource kann nicht geändert werden, nachdem er erstellt, aber wenn Sie eine identische geografische Region für Update angegeben ist, wird die Anforderung erfolgreich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt erforderlich. Ruft ab oder legt den Sku-Namen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Diese Tags können verwendet werden, für die Anzeige und gruppieren diese Ressource (über Ressourcengruppen hinweg). Für eine Ressource kann maximal 15 Tags bereitgestellt werden. Jedes Tag muss es sich um einen Schlüssel mit einer Länge von 128 Zeichen nicht überschreiten und einen Wert mit einer Länge von maximal 256 Zeichen verfügen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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