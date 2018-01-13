<Type Name="DatabaseBackupSetting" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting">
  <TypeSignature Language="C#" Value="public class DatabaseBackupSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseBackupSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseBackupSetting" />
  <TypeSignature Language="F#" Value="type DatabaseBackupSetting = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a7135-101">Datenbank-sicherungseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="a7135-101">Database backup settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBackupSetting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7135-102">Initialisiert eine neue Instanz der DatabaseBackupSetting-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7135-102">Initializes a new instance of the DatabaseBackupSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseBackupSetting (string databaseType, string name = null, string connectionStringName = null, string connectionString = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string databaseType, string name, string connectionStringName, string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (databaseType As String, Optional name As String = null, Optional connectionStringName As String = null, Optional connectionString As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting : string * string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting (databaseType, name, connectionStringName, connectionString)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="databaseType" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="connectionStringName" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseType"><span data-ttu-id="a7135-103">Datenbanktyp (z. B. SqlAzure / MySql).</span><span class="sxs-lookup"><span data-stu-id="a7135-103">Database type (e.g. SqlAzure / MySql).</span></span>
            <span data-ttu-id="a7135-104">Folgende Werte sind möglich: "SqlAzure", "MySql", "LocalMySql"</span><span class="sxs-lookup"><span data-stu-id="a7135-104">Possible values include: 'SqlAzure', 'MySql', 'LocalMySql'</span></span></param>
        <param name="name">To be added.</param>
        <param name="connectionStringName"><span data-ttu-id="a7135-105">Enthält ein Name einer Verbindungszeichenfolge, die mit der SiteConfig.ConnectionStrings verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a7135-105">Contains a connection string name that is linked to the SiteConfig.ConnectionStrings.</span></span>
            <span data-ttu-id="a7135-106">Dies wird verwendet, während der Wiederherstellung mit Überschreiben Sie Verbindungsoptionen für Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="a7135-106">This is used during restore with overwrite connection strings options.</span></span></param>
        <param name="connectionString"><span data-ttu-id="a7135-107">Enthält eine Verbindungszeichenfolge zu einer Datenbank, die gerade gesichert oder wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="a7135-107">Contains a connection string to a database which is being backed up or restored.</span></span> <span data-ttu-id="a7135-108">Wenn die Wiederherstellung in eine neue Datenbank geschehen soll, ist der Datenbankname in das neue Projekt.</span><span class="sxs-lookup"><span data-stu-id="a7135-108">If the restore should happen to a new database, the database name inside is the new one.</span></span></param>
        <summary>
            <span data-ttu-id="a7135-109">Initialisiert eine neue Instanz der DatabaseBackupSetting-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7135-109">Initializes a new instance of the DatabaseBackupSetting class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7135-110">Ruft ab oder legt sie fest, enthält eine Verbindungszeichenfolge zu einer Datenbank, die gerade gesichert oder wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="a7135-110">Gets or sets contains a connection string to a database which is being backed up or restored.</span></span> <span data-ttu-id="a7135-111">Wenn die Wiederherstellung in eine neue Datenbank geschehen soll, ist der Datenbankname in das neue Projekt.</span><span class="sxs-lookup"><span data-stu-id="a7135-111">If the restore should happen to a new database, the database name inside is the new one.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionStringName">
      <MemberSignature Language="C#" Value="public string ConnectionStringName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionStringName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionStringName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionStringName As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionStringName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.ConnectionStringName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionStringName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7135-112">Ruft ab oder legt enthält Name einer Verbindungszeichenfolge, die mit der SiteConfig.ConnectionStrings verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="a7135-112">Gets or sets contains a connection string name that is linked to the SiteConfig.ConnectionStrings.</span></span>
            <span data-ttu-id="a7135-113">Dies wird verwendet, während der Wiederherstellung mit Überschreiben Sie Verbindungsoptionen für Zeichenfolgen.</span><span class="sxs-lookup"><span data-stu-id="a7135-113">This is used during restore with overwrite connection strings options.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseType">
      <MemberSignature Language="C#" Value="public string DatabaseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.DatabaseType" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseType As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseType : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.DatabaseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7135-114">Ruft ab oder legt ihn fest Datenbanktyp (z. B. SqlAzure / MySql).</span><span class="sxs-lookup"><span data-stu-id="a7135-114">Gets or sets database type (e.g. SqlAzure / MySql).</span></span> <span data-ttu-id="a7135-115">Folgende Werte sind möglich: "SqlAzure", "MySql", "LocalMySql"</span><span class="sxs-lookup"><span data-stu-id="a7135-115">Possible values include: 'SqlAzure', 'MySql', 'LocalMySql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="databaseBackupSetting.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7135-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a7135-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a7135-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a7135-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>