<Type Name="SyncGroupSchema" FullName="Microsoft.Azure.Management.Sql.Models.SyncGroupSchema">
  <TypeSignature Language="C#" Value="public class SyncGroupSchema" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncGroupSchema extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncGroupSchema" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncGroupSchema" />
  <TypeSignature Language="F#" Value="type SyncGroupSchema = class" />
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
            Eigenschaften des synchronisierungsgruppenschema.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SyncGroupSchema-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncGroupSchema (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; tables = null, string masterSyncMemberName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; tables, string masterSyncMemberName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional tables As IList(Of SyncGroupSchemaTable) = null, Optional masterSyncMemberName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchema : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncGroupSchema" Usage="new Microsoft.Azure.Management.Sql.Models.SyncGroupSchema (tables, masterSyncMemberName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt;" />
        <Parameter Name="masterSyncMemberName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tables">Liste der Tabellen im synchronisierungsgruppenschema.</param>
        <param name="masterSyncMemberName">Name des master Sync-Element, aus denen das Schema ist.</param>
        <summary>
            Initialisiert eine neue Instanz der SyncGroupSchema-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterSyncMemberName">
      <MemberSignature Language="C#" Value="public string MasterSyncMemberName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterSyncMemberName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.MasterSyncMemberName" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterSyncMemberName As String" />
      <MemberSignature Language="F#" Value="member this.MasterSyncMemberName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.MasterSyncMemberName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="masterSyncMemberName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Namen master Sync-Elements, aus denen das Schema ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; Tables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; Tables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.Tables" />
      <MemberSignature Language="VB.NET" Value="Public Property Tables As IList(Of SyncGroupSchemaTable)" />
      <MemberSignature Language="F#" Value="member this.Tables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.SyncGroupSchema.Tables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupSchemaTable&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Tabellen im synchronisierungsgruppenschema fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>