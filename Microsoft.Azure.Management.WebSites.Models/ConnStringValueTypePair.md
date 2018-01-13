<Type Name="ConnStringValueTypePair" FullName="Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair">
  <TypeSignature Language="C#" Value="public class ConnStringValueTypePair" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConnStringValueTypePair extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair" />
  <TypeSignature Language="VB.NET" Value="Public Class ConnStringValueTypePair" />
  <TypeSignature Language="F#" Value="type ConnStringValueTypePair = class" />
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
            <span data-ttu-id="7f487-101">Datenbank-verbindungszeichenwert Paar eingeben.</span><span class="sxs-lookup"><span data-stu-id="7f487-101">Database connection string value to type pair.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f487-102">Initialisiert eine neue Instanz der ConnStringValueTypePair-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f487-102">Initializes a new instance of the ConnStringValueTypePair class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConnStringValueTypePair (string value, Microsoft.Azure.Management.WebSites.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string value, valuetype Microsoft.Azure.Management.WebSites.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.#ctor(System.String,Microsoft.Azure.Management.WebSites.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (value As String, type As ConnectionStringType)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair : string * Microsoft.Azure.Management.WebSites.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair" Usage="new Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair (value, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.WebSites.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="value"><span data-ttu-id="7f487-103">Wert-Paars.</span><span class="sxs-lookup"><span data-stu-id="7f487-103">Value of pair.</span></span></param>
        <param name="type"><span data-ttu-id="7f487-104">Der Typ der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="7f487-104">Type of database.</span></span> <span data-ttu-id="7f487-105">Folgende Werte sind möglich: "MySql", "SQLServer", "SQLAzure", "Benutzerdefiniert", 'NotificationHub', "ServiceBus", "EventHub", "ApiHub", "DocDb", "RedisCache", "PostgreSQL"</span><span class="sxs-lookup"><span data-stu-id="7f487-105">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache', 'PostgreSQL'</span></span></param>
        <summary>
            <span data-ttu-id="7f487-106">Initialisiert eine neue Instanz der ConnStringValueTypePair-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7f487-106">Initializes a new instance of the ConnStringValueTypePair class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.ConnectionStringType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.WebSites.Models.ConnectionStringType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ConnectionStringType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.WebSites.Models.ConnectionStringType with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.Type" />
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
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ConnectionStringType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f487-107">Ruft ab oder legt ihn fest-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="7f487-107">Gets or sets type of database.</span></span> <span data-ttu-id="7f487-108">Folgende Werte sind möglich: "MySql", "SQLServer", "SQLAzure", "Benutzerdefiniert", 'NotificationHub', "ServiceBus", "EventHub", "ApiHub", "DocDb", "RedisCache", "PostgreSQL"</span><span class="sxs-lookup"><span data-stu-id="7f487-108">Possible values include: 'MySql', 'SQLServer', 'SQLAzure', 'Custom', 'NotificationHub', 'ServiceBus', 'EventHub', 'ApiHub', 'DocDb', 'RedisCache', 'PostgreSQL'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="connStringValueTypePair.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f487-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7f487-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7f487-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7f487-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ConnStringValueTypePair.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f487-111">Ruft ab, oder legt ihn fest-Paars.</span><span class="sxs-lookup"><span data-stu-id="7f487-111">Gets or sets value of pair.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>