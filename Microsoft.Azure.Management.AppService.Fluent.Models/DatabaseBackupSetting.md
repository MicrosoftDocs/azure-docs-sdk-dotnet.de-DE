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
            Datenbank-sicherungseinstellungen.
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
            Initialisiert eine neue Instanz der DatabaseBackupSetting-Klasse.
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
        <param name="databaseType">Datenbanktyp (z. B. SqlAzure / MySql).
            Folgende Werte sind möglich: "SqlAzure", "MySql", "LocalMySql"</param>
        <param name="name">To be added.</param>
        <param name="connectionStringName">Enthält ein Name einer Verbindungszeichenfolge, die mit der SiteConfig.ConnectionStrings verknüpft ist.
            Dies wird verwendet, während der Wiederherstellung mit Überschreiben Sie Verbindungsoptionen für Zeichenfolgen.</param>
        <param name="connectionString">Enthält eine Verbindungszeichenfolge zu einer Datenbank, die gerade gesichert oder wiederhergestellt. Wenn die Wiederherstellung in eine neue Datenbank geschehen soll, ist der Datenbankname in das neue Projekt.</param>
        <summary>
            Initialisiert eine neue Instanz der DatabaseBackupSetting-Klasse.
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
            Ruft ab oder legt sie fest, enthält eine Verbindungszeichenfolge zu einer Datenbank, die gerade gesichert oder wiederhergestellt. Wenn die Wiederherstellung in eine neue Datenbank geschehen soll, ist der Datenbankname in das neue Projekt.
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
            Ruft ab oder legt enthält Name einer Verbindungszeichenfolge, die mit der SiteConfig.ConnectionStrings verknüpft ist.
            Dies wird verwendet, während der Wiederherstellung mit Überschreiben Sie Verbindungsoptionen für Zeichenfolgen.
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
            Ruft ab oder legt ihn fest Datenbanktyp (z. B. SqlAzure / MySql). Folgende Werte sind möglich: "SqlAzure", "MySql", "LocalMySql"
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