<Type Name="Registry" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Registry">
  <TypeSignature Language="C#" Value="public class Registry : Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Registry extends Microsoft.Azure.Management.ContainerRegistry.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Registry" />
  <TypeSignature Language="VB.NET" Value="Public Class Registry&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Registry = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ContainerRegistry.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein Objekt, das eine containerregistrierung darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Registrierung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Registry (string location, Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string loginServer = null, Nullable&lt;DateTime&gt; creationDate = null, string provisioningState = null, Microsoft.Azure.Management.ContainerRegistry.Models.Status status = null, Nullable&lt;bool&gt; adminUserEnabled = null, Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.ContainerRegistry.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string loginServer, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string provisioningState, class Microsoft.Azure.Management.ContainerRegistry.Models.Status status, valuetype System.Nullable`1&lt;bool&gt; adminUserEnabled, class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.#ctor(System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.ContainerRegistry.Models.Status,System.Nullable{System.Boolean},Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry : string * Microsoft.Azure.Management.ContainerRegistry.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.ContainerRegistry.Models.Status * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Registry" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Registry (location, sku, id, name, type, tags, loginServer, creationDate, provisioningState, status, adminUserEnabled, storageAccount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="loginServer" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.ContainerRegistry.Models.Status" />
        <Parameter Name="adminUserEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties" />
      </Parameters>
      <Docs>
        <param name="location">Der Speicherort der Ressource. Dies kann nicht geändert werden, nachdem die Ressource erstellt wurde.</param>
        <param name="sku">Die SKU der containerregistrierung.</param>
        <param name="id">Die Ressourcen-ID.</param>
        <param name="name">Der Name der Ressource.</param>
        <param name="type">Der Typ der Ressource.</param>
        <param name="tags">Die Tags der Ressource.</param>
        <param name="loginServer">Die URL, die sich in der containerregistrierung verwendet werden kann.</param>
        <param name="creationDate">Das Erstellungsdatum der containerregistrierung im ISO8601-Format.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der containerregistrierung zu dem Zeitpunkt, zu der Vorgang aufgerufen wurde. Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</param>
        <param name="status">Der Status der containerregistrierung zum Zeitpunkt der Vorgang aufgerufen wurde.</param>
        <param name="adminUserEnabled">Der Wert, der angibt, ob die adminbenutzer aktiviert ist.</param>
        <param name="storageAccount">Die Eigenschaften des Speicherkontos für die containerregistrierung. Gilt nur für klassische SKU.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Registrierung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AdminUserEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AdminUserEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AdminUserEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.AdminUserEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminUserEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert, der angibt, ob die adminbenutzer aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Erstellungsdatum der containerregistrierung im ISO8601-Format ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginServer">
      <MemberSignature Language="C#" Value="public string LoginServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoginServer As String" />
      <MemberSignature Language="F#" Value="member this.LoginServer : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.LoginServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loginServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL, die zum Anmelden verwendet werden kann, in der containerregistrierung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus der der containerregistrierung zu dem Zeitpunkt, der Vorgang aufgerufen wurde. Folgende Werte sind möglich: "Erstellen", "Aktualisieren", "Löschen", "erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.ContainerRegistry.Models.Sku with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die SKU der containerregistrierung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.Status Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.Status Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Status" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.ContainerRegistry.Models.Status" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.Status</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status der containerregistrierung ab, zu dem Zeitpunkt, der Vorgang aufgerufen wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As StorageAccountProperties" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Registry.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.StorageAccountProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften des Speicherkontos für die containerregistrierung fest. Gilt nur für klassische SKU.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Registry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="registry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
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
  </Members>
</Type>