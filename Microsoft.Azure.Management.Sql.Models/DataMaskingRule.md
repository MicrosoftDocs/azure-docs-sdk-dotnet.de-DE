<Type Name="DataMaskingRule" FullName="Microsoft.Azure.Management.Sql.Models.DataMaskingRule">
  <TypeSignature Language="C#" Value="public class DataMaskingRule : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataMaskingRule extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DataMaskingRule" />
  <TypeSignature Language="VB.NET" Value="Public Class DataMaskingRule&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DataMaskingRule = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt eine datenmaskierungsregel Datenbank dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataMaskingRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataMaskingRule (string schemaName, string tableName, string columnName, Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id = null, string name = null, string type = null, string dataMaskingRuleId = null, string aliasName = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState = null, string numberFrom = null, string numberTo = null, string prefixSize = null, string suffixSize = null, string replacementString = null, string location = null, string kind = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string schemaName, string tableName, string columnName, valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction maskingFunction, string id, string name, string type, string dataMaskingRuleId, string aliasName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; ruleState, string numberFrom, string numberTo, string prefixSize, string suffixSize, string replacementString, string location, string kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DataMaskingFunction,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState},System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (schemaName As String, tableName As String, columnName As String, maskingFunction As DataMaskingFunction, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional dataMaskingRuleId As String = null, Optional aliasName As String = null, Optional ruleState As Nullable(Of DataMaskingRuleState) = null, Optional numberFrom As String = null, Optional numberTo As String = null, Optional prefixSize As String = null, Optional suffixSize As String = null, Optional replacementString As String = null, Optional location As String = null, Optional kind As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule : string * string * string * Microsoft.Azure.Management.Sql.Models.DataMaskingFunction * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.DataMaskingRule" Usage="new Microsoft.Azure.Management.Sql.Models.DataMaskingRule (schemaName, tableName, columnName, maskingFunction, id, name, type, dataMaskingRuleId, aliasName, ruleState, numberFrom, numberTo, prefixSize, suffixSize, replacementString, location, kind)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="columnName" Type="System.String" />
        <Parameter Name="maskingFunction" Type="Microsoft.Azure.Management.Sql.Models.DataMaskingFunction" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="dataMaskingRuleId" Type="System.String" />
        <Parameter Name="aliasName" Type="System.String" />
        <Parameter Name="ruleState" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;" />
        <Parameter Name="numberFrom" Type="System.String" />
        <Parameter Name="numberTo" Type="System.String" />
        <Parameter Name="prefixSize" Type="System.String" />
        <Parameter Name="suffixSize" Type="System.String" />
        <Parameter Name="replacementString" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="schemaName">Der Schemaname, auf dem die Data Masking-Regel angewendet wird.</param>
        <param name="tableName">Der Tabellenname, auf dem die Data Masking-Regel angewendet wird.</param>
        <param name="columnName">Der Spaltenname, auf dem die Data Masking-Regel angewendet wird.</param>
        <param name="maskingFunction">Das Maskierungsfunktion, die für die datenmaskierungsregel verwendet wird. Folgende Werte sind möglich: 'Default', "CCN", "Email", "Zahl", "SSN", "Text"</param>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="dataMaskingRuleId">Die Regel-ID</param>
        <param name="aliasName">Der Aliasname. Dies ist ein legacy-Parameter und wird nicht mehr verwendet.</param>
        <param name="ruleState">Der Regelstatus. Löschen eine Regel verwendet. Um eine vorhandene Regel zu löschen, geben Sie die SchemaName, der Tabellenname, der Spaltenname, MaskingFunction, und RuleState als deaktiviert.
            Wenn die Regel bereits vorhanden ist, wird die Regel mit RuleState festgelegt aktiviert ist, unabhängig vom angegebenen Wert des RuleState erstellt werden. Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</param>
        <param name="numberFrom">Die von der maskierungsregel NumberFrom-Eigenschaft. Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</param>
        <param name="numberTo">Die von der die datenmaskierungsregel NumberTo-Eigenschaft. Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.</param>
        <param name="prefixSize">Wenn MaskingFunction auf Text, die Anzahl der Zeichen am Anfang der Zeichenfolge ohne Maskierung angezeigt festgelegt ist. Andernfalls wird dieser Parameter ignoriert.</param>
        <param name="suffixSize">Wenn MaskingFunction auf Text, die Anzahl der Zeichen am Ende der Zeichenfolge ohne Maskierung angezeigt festgelegt ist.
            Andernfalls wird dieser Parameter ignoriert.</param>
        <param name="replacementString">Wenn MaskingFunction auf Text, das Zeichen, das zum Maskieren der nicht offen gelegten Teils der Zeichenfolge festgelegt ist.
            Andernfalls wird dieser Parameter ignoriert.</param>
        <param name="location">Der Speicherort der datenmaskierungsregel.</param>
        <param name="kind">Die Art der Datenmaskierungsregel. Metadaten für die Azure-Portal verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der DataMaskingRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AliasName">
      <MemberSignature Language="C#" Value="public string AliasName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AliasName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberSignature Language="VB.NET" Value="Public Property AliasName As String" />
      <MemberSignature Language="F#" Value="member this.AliasName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.AliasName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.aliasName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Aliasnamen fest. Dies ist ein legacy-Parameter und wird nicht mehr verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnName">
      <MemberSignature Language="C#" Value="public string ColumnName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ColumnName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnName As String" />
      <MemberSignature Language="F#" Value="member this.ColumnName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ColumnName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columnName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Spalte, auf dem die Data Masking-Regel angewendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataMaskingRuleId">
      <MemberSignature Language="C#" Value="public string DataMaskingRuleId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataMaskingRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataMaskingRuleId As String" />
      <MemberSignature Language="F#" Value="member this.DataMaskingRuleId : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.DataMaskingRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Regel-ID ab
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Art der Datenmaskierungsregel. Metadaten für die Azure-Portal verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Speicherort der datenmaskierungsregel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaskingFunction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingFunction MaskingFunction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberSignature Language="VB.NET" Value="Public Property MaskingFunction As DataMaskingFunction" />
      <MemberSignature Language="F#" Value="member this.MaskingFunction : Microsoft.Azure.Management.Sql.Models.DataMaskingFunction with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.MaskingFunction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maskingFunction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.DataMaskingFunction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Maskierungsfunktion, die für die datenmaskierungsregel verwendet wird. Folgende Werte sind möglich: 'Default', "CCN", "Email", "Zahl", "SSN", "Text"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberFrom">
      <MemberSignature Language="C#" Value="public string NumberFrom { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberFrom" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberFrom As String" />
      <MemberSignature Language="F#" Value="member this.NumberFrom : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberFrom" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberFrom")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest NumberFrom-Eigenschaft der Maskierung. Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberTo">
      <MemberSignature Language="C#" Value="public string NumberTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NumberTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberTo As String" />
      <MemberSignature Language="F#" Value="member this.NumberTo : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.NumberTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die NumberTo-Eigenschaft der datenmaskierungsregel.
            Erforderlich, wenn MaskingFunction festgelegt ist, werden andernfalls dieser Parameter ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefixSize">
      <MemberSignature Language="C#" Value="public string PrefixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrefixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefixSize As String" />
      <MemberSignature Language="F#" Value="member this.PrefixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.PrefixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.prefixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Text, die Anzahl der Zeichen am Anfang der Zeichenfolge ohne Maskierung angezeigt MaskingFunction angegeben ist.
            Andernfalls wird dieser Parameter ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacementString">
      <MemberSignature Language="C#" Value="public string ReplacementString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplacementString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplacementString As String" />
      <MemberSignature Language="F#" Value="member this.ReplacementString : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.ReplacementString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replacementString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob MaskingFunction auf Text, das Zeichen, das zum Maskieren der nicht offen gelegten Teils der Zeichenfolge festgelegt ist. Andernfalls wird dieser Parameter ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; RuleState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleState As Nullable(Of DataMaskingRuleState)" />
      <MemberSignature Language="F#" Value="member this.RuleState : Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.RuleState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ruleState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.DataMaskingRuleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Regelstatus fest. Löschen eine Regel verwendet. Um eine vorhandene Regel zu löschen, geben Sie die SchemaName, der Tabellenname, der Spaltenname, MaskingFunction, und RuleState als deaktiviert. Wenn die Regel bereits vorhanden ist, wird die Regel mit RuleState festgelegt aktiviert ist, unabhängig vom angegebenen Wert des RuleState erstellt werden.
            Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schemanamen, auf dem die Data Masking-Regel angewendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuffixSize">
      <MemberSignature Language="C#" Value="public string SuffixSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SuffixSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberSignature Language="VB.NET" Value="Public Property SuffixSize As String" />
      <MemberSignature Language="F#" Value="member this.SuffixSize : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.SuffixSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suffixSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Text, die Anzahl der Zeichen am Ende der Zeichenfolge ohne Maskierung angezeigt MaskingFunction angegeben ist. Andernfalls wird dieser Parameter ignoriert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DataMaskingRule.TableName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Tabelle, auf dem die Data Masking-Regel angewendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DataMaskingRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataMaskingRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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