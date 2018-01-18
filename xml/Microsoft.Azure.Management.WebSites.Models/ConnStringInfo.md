<Type Name="ConnStringInfo" FullName="Microsoft.Azure.Management.WebSites.Models.ConnStringInfo">
  <TypeSignature Language="C#" Value="public class ConnStringInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnStringInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnStringInfo" />
  <TypeSignature Language="F#" Value="type ConnStringInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="78203-101">Datenbank-Verbindungszeichenfolge übernommen.</span><span class="sxs-lookup"><span data-stu-id="78203-101">Database connection string information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="78203-102">Initialisiert eine neue Instanz der ConnStringInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="78203-102">Initializes a new instance of the ConnStringInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringInfo (string name = null, string connectionString = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string connectionString, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.ConnectionStringType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional connectionString As String = null, Optional type As Nullable(Of ConnectionStringType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ConnStringInfo : string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ConnStringInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.ConnStringInfo (name, connectionString, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="78203-103">Der Name der Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="78203-103">Name of connection string.</span></span></param>
        <param name="connectionString"><span data-ttu-id="78203-104">Der Verbindungszeichenfolgenwert.</span><span class="sxs-lookup"><span data-stu-id="78203-104">Connection string value.</span></span></param>
        <param name="type"><span data-ttu-id="78203-105">Der Typ der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="78203-105">Type of database.</span></span> <span data-ttu-id="78203-106">Folgende Werte sind möglich: "MySql", "SQLServer", "SQLAzure", "Benutzerdefiniert", 'NotificationHub', "ServiceBus", "EventHub", "ApiHub", "DocDb", "RedisCache", "PostgreSQL"</span><span class="sxs-lookup"><span data-stu-id="78203-106">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache', 'PostgreSQL'</span></span></param>
        <summary>
            <span data-ttu-id="78203-107">Initialisiert eine neue Instanz der ConnStringInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="78203-107">Initializes a new instance of the ConnStringInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="78203-108">Ruft ab, oder legt ihn fest verbindungszeichenwert.</span><span class="sxs-lookup"><span data-stu-id="78203-108">Gets or sets connection string value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="78203-109">Ruft ab oder legt den Namen der Verbindungszeichenfolge fest.</span><span class="sxs-lookup"><span data-stu-id="78203-109">Gets or sets name of connection string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ConnectionStringType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnStringInfo.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ConnectionStringType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78203-110">Ruft ab oder legt ihn fest-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="78203-110">Gets or sets type of database.</span></span> <span data-ttu-id="78203-111">Folgende Werte sind möglich: "MySql", "SQLServer", "SQLAzure", "Benutzerdefiniert", 'NotificationHub', "ServiceBus", "EventHub", "ApiHub", "DocDb", "RedisCache", "PostgreSQL"</span><span class="sxs-lookup"><span data-stu-id="78203-111">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache', 'PostgreSQL'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>