<Type Name="SqlRuleAction" FullName="Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction">
  <TypeSignature Language="C#" Value="public class SqlRuleAction : Microsoft.Azure.Management.ServiceBus.Models.Action" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SqlRuleAction extends Microsoft.Azure.Management.ServiceBus.Models.Action" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlRuleAction&#xA;Inherits Action" />
  <TypeSignature Language="F#" Value="type SqlRuleAction = class&#xA;    inherit Action" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Action</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Satz von Aktionen, die geschrieben werden, in der SQL-basierte Syntax, die für eine ServiceBus.Messaging.BrokeredMessage ausgeführt wird
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SqlRuleAction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression = null, Nullable&lt;int&gt; compatibilityLevel = null, Nullable&lt;bool&gt; requiresPreprocessing = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression, valuetype System.Nullable`1&lt;int32&gt; compatibilityLevel, valuetype System.Nullable`1&lt;bool&gt; requiresPreprocessing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sqlExpression As String = null, Optional compatibilityLevel As Nullable(Of Integer) = null, Optional requiresPreprocessing As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SqlRuleAction (sqlExpression, compatibilityLevel, requiresPreprocessing)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresPreprocessing" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL-Ausdruck. z. B. MyProperty = 'ABC'</param>
        <param name="compatibilityLevel">Diese Eigenschaft ist für eine spätere Verwendung vorgesehen. Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.</param>
        <param name="requiresPreprocessing">Ein Wert, der angibt, ob die Aktion für eine vorverarbeitung erforderlich ist.</param>
        <summary>
            Initialisiert eine neue Instanz der SqlRuleAction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>