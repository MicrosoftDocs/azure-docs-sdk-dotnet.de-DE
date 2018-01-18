<Type Name="SyncGroupSchemaTableColumn" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn">
  <TypeSignature Language="C#" Value="public class SyncGroupSchemaTableColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupSchemaTableColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupSchemaTableColumn" />
  <TypeSignature Language="F#" Value="type SyncGroupSchemaTableColumn = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a5284-101">Eigenschaften der Spalte in der Tabelle der Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="a5284-101">Properties of column in sync group table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTableColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5284-102">Initialisiert eine neue Instanz der SyncGroupSchemaTableColumn-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a5284-102">Initializes a new instance of the SyncGroupSchemaTableColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchemaTableColumn (string quotedName = null, string dataSize = null, string dataType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string quotedName, string dataSize, string dataType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional quotedName As String = null, Optional dataSize As String = null, Optional dataType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn : string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn (quotedName, dataSize, dataType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="quotedName" Type="System.String" />
        <Parameter Name="dataSize" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="quotedName"><span data-ttu-id="a5284-103">In Anführungszeichen Name der Tabellenspalte für Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="a5284-103">Quoted name of sync group table column.</span></span></param>
        <param name="dataSize"><span data-ttu-id="a5284-104">Die Größe der Daten der Spalte.</span><span class="sxs-lookup"><span data-stu-id="a5284-104">Data size of the column.</span></span></param>
        <param name="dataType"><span data-ttu-id="a5284-105">Datentyp der Spalte.</span><span class="sxs-lookup"><span data-stu-id="a5284-105">Data type of the column.</span></span></param>
        <summary>
            <span data-ttu-id="a5284-106">Initialisiert eine neue Instanz der SyncGroupSchemaTableColumn-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a5284-106">Initializes a new instance of the SyncGroupSchemaTableColumn class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSize">
      <MemberSignature Language="C#" Value="public string DataSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataSize" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSize As String" />
      <MemberSignature Language="F#" Value="member this.DataSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5284-107">Ruft ab oder legt die Größe der Daten der Spalte.</span><span class="sxs-lookup"><span data-stu-id="a5284-107">Gets or sets data size of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5284-108">Ruft ab oder legt den Datentyp der Spalte.</span><span class="sxs-lookup"><span data-stu-id="a5284-108">Gets or sets data type of the column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTableColumn.QuotedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a5284-109">Ruft ab, oder legt ihn fest in Anführungszeichen Name der Tabellenspalte für Sync-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="a5284-109">Gets or sets quoted name of sync group table column.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>