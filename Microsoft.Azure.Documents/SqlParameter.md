<Type Name="SqlParameter" FullName="Microsoft.Azure.Documents.SqlParameter">
  <TypeSignature Language="C#" Value="public sealed class SqlParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SqlParameter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlParameter" />
  <TypeSignature Language="F#" Value="type SqlParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt einen zugeordneten Parameter <see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" /> im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>
            Azure Cosmos-DB-SQL-Parameter sind Name / Wert-Paaren, die in parametrisierten Abfragen verwiesen wird. Im Gegensatz zu haben nicht in Relation SQL-Datenbanken, zugeordnet.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Parameters.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Klasse mit dem Namen des Parameters für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>Namen der Parameter müssen beginnen mit ' @' und ein gültiger SQL-Bezeichner sein.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlParameter (string name, object value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, object value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SqlParameter.#ctor(System.String,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.SqlParameter : string * obj -&gt; Microsoft.Azure.Documents.SqlParameter" Usage="new Microsoft.Azure.Documents.SqlParameter (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Parameters.</param>
        <param name="value">Der Wert des Parameters.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.SqlParameter" /> Klasse mit dem Namen und Wert des Parameters für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>Namen der Parameter müssen beginnen mit ' @' und ein gültiger SQL-Bezeichner sein. Der Wert ruft serialisiert und an die Abfrage als JSON übergeben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Parameters für den Azure-Cosmos-DB-Dienst fest.
            </summary>
        <value>Der Name des Parameters.</value>
        <remarks>Namen der Parameter müssen beginnen mit ' @' und ein gültiger SQL-Bezeichner sein.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public object Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.SqlParameter.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As Object" />
      <MemberSignature Language="F#" Value="member this.Value : obj with get, set" Usage="Microsoft.Azure.Documents.SqlParameter.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(Name="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert des Parameters für den Azure-Cosmos-DB-Dienst fest.
            </summary>
        <value>Der Wert des Parameters.</value>
        <remarks>Der Wert ruft serialisiert und an die Abfrage als JSON übergeben.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>