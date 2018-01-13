<Type Name="VaultProperties" FullName="Microsoft.Azure.Management.KeyVault.Models.VaultProperties">
  <TypeSignature Language="C#" Value="public class VaultProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.VaultProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultProperties" />
  <TypeSignature Language="F#" Value="type VaultProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften des Tresors
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VaultProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties (Guid tenantId, Microsoft.Azure.Management.KeyVault.Models.Sku sku, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; accessPolicies = null, string vaultUri = null, Nullable&lt;bool&gt; enabledForDeployment = null, Nullable&lt;bool&gt; enabledForDiskEncryption = null, Nullable&lt;bool&gt; enabledForTemplateDeployment = null, Nullable&lt;bool&gt; enableSoftDelete = null, Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; createMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid tenantId, class Microsoft.Azure.Management.KeyVault.Models.Sku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; accessPolicies, string vaultUri, valuetype System.Nullable`1&lt;bool&gt; enabledForDeployment, valuetype System.Nullable`1&lt;bool&gt; enabledForDiskEncryption, valuetype System.Nullable`1&lt;bool&gt; enabledForTemplateDeployment, valuetype System.Nullable`1&lt;bool&gt; enableSoftDelete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; createMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.#ctor(System.Guid,Microsoft.Azure.Management.KeyVault.Models.Sku,System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.KeyVault.Models.CreateMode})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.VaultProperties : Guid * Microsoft.Azure.Management.KeyVault.Models.Sku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.VaultProperties" Usage="new Microsoft.Azure.Management.KeyVault.Models.VaultProperties (tenantId, sku, accessPolicies, vaultUri, enabledForDeployment, enabledForDiskEncryption, enabledForTemplateDeployment, enableSoftDelete, createMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.KeyVault.Models.Sku" />
        <Parameter Name="accessPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt;" />
        <Parameter Name="vaultUri" Type="System.String" />
        <Parameter Name="enabledForDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForDiskEncryption" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForTemplateDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableSoftDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="createMode" Type="System.Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt;" />
      </Parameters>
      <Docs>
        <param name="tenantId">Die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.</param>
        <param name="sku">SKU-Informationen</param>
        <param name="accessPolicies">Ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen. Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.</param>
        <param name="vaultUri">Der URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche.</param>
        <param name="enabledForDeployment">Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.</param>
        <param name="enabledForDiskEncryption">Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.</param>
        <param name="enabledForTemplateDeployment">Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.</param>
        <param name="enableSoftDelete">Eigenschaft, um anzugeben, ob die Funktion "vorläufiges löschen" für diesen schlüsseltresor aktiviert ist. Wert "false" werden nicht angenommen.</param>
        <param name="createMode">Der Tresor erstellen Modus, um anzugeben, ob der Tresor oder nicht wiederhergestellt werden müssen. Folgende Werte sind möglich: 'Wiederherstellen', 'Default'</param>
        <summary>
            Initialisiert eine neue Instanz der VaultProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; AccessPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; AccessPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.AccessPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessPolicies As IList(Of AccessPolicyEntry)" />
      <MemberSignature Language="F#" Value="member this.AccessPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.AccessPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accessPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen. Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As Nullable(Of CreateMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMode : Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Erstellen des Tresors Modus, um anzugeben, ob der Tresor oder nicht wiederhergestellt werden müssen. Folgende Werte sind möglich: 'Wiederherstellen', 'Default'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDiskEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDiskEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDiskEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDiskEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDiskEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDiskEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForTemplateDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForTemplateDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForTemplateDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForTemplateDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForTemplateDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForTemplateDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSoftDelete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableSoftDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableSoftDelete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnableSoftDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSoftDelete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableSoftDelete : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnableSoftDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableSoftDelete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaft, um anzugeben, ob die Funktion "vorläufiges löschen" für diesen schlüsseltresor aktiviert ist. Wert "false" werden nicht angenommen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.KeyVault.Models.Sku with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest SKU-details
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="vaultProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="VaultUri">
      <MemberSignature Language="C#" Value="public string VaultUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.VaultUri" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultUri As String" />
      <MemberSignature Language="F#" Value="member this.VaultUri : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.VaultUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vaultUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>