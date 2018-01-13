<Type Name="StorageMigrationOptions" FullName="Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions">
  <TypeSignature Language="C#" Value="public class StorageMigrationOptions : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageMigrationOptions extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageMigrationOptions&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type StorageMigrationOptions = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Optionen für die Migration von app-Inhalten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageMigrationOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageMigrationOptions (string id = null, string name = null, string kind = null, string type = null, string azurefilesConnectionString = null, string azurefilesShare = null, Nullable&lt;bool&gt; switchSiteAfterMigration = null, Nullable&lt;bool&gt; blockWriteAccessToSite = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string azurefilesConnectionString, string azurefilesShare, valuetype System.Nullable`1&lt;bool&gt; switchSiteAfterMigration, valuetype System.Nullable`1&lt;bool&gt; blockWriteAccessToSite) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional azurefilesConnectionString As String = null, Optional azurefilesShare As String = null, Optional switchSiteAfterMigration As Nullable(Of Boolean) = null, Optional blockWriteAccessToSite As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions : string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions" Usage="new Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions (id, name, kind, type, azurefilesConnectionString, azurefilesShare, switchSiteAfterMigration, blockWriteAccessToSite)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="azurefilesConnectionString" Type="System.String" />
        <Parameter Name="azurefilesShare" Type="System.String" />
        <Parameter Name="switchSiteAfterMigration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="blockWriteAccessToSite" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="azurefilesConnectionString">Migrieren der Verbindungszeichenfolge.</param>
        <param name="azurefilesShare">Migrieren teilen.</param>
        <param name="switchSiteAfterMigration">&lt;Code&gt;"true"&lt;/code&gt;Wenn die app soll, mehr ist, andernfalls umgeschaltet werden &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <param name="blockWriteAccessToSite">&lt;Code&gt;"true"&lt;/code&gt; Wenn die app, nur während des Kopiervorgangs gelesen wurde, andernfalls werden soll &lt;Code&gt;"false"&lt;/code&gt;.</param>
        <summary>
            Initialisiert eine neue Instanz der StorageMigrationOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzurefilesConnectionString">
      <MemberSignature Language="C#" Value="public string AzurefilesConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzurefilesConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.AzurefilesConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property AzurefilesConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.AzurefilesConnectionString : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.AzurefilesConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azurefilesConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt migrieren Verbindungszeichenfolge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzurefilesShare">
      <MemberSignature Language="C#" Value="public string AzurefilesShare { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzurefilesShare" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.AzurefilesShare" />
      <MemberSignature Language="VB.NET" Value="Public Property AzurefilesShare As String" />
      <MemberSignature Language="F#" Value="member this.AzurefilesShare : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.AzurefilesShare" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azurefilesShare")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest migrieren freigeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockWriteAccessToSite">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; BlockWriteAccessToSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; BlockWriteAccessToSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.BlockWriteAccessToSite" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockWriteAccessToSite As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.BlockWriteAccessToSite : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.BlockWriteAccessToSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blockWriteAccessToSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app, nur während des Kopiervorgangs gelesen wurde, andernfalls werden soll &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SwitchSiteAfterMigration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SwitchSiteAfterMigration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SwitchSiteAfterMigration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.SwitchSiteAfterMigration" />
      <MemberSignature Language="VB.NET" Value="Public Property SwitchSiteAfterMigration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SwitchSiteAfterMigration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.StorageMigrationOptions.SwitchSiteAfterMigration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.switchSiteAfterMigration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app soll, mehr ist, andernfalls umgeschaltet werden &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>