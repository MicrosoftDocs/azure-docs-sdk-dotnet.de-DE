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
            <span data-ttu-id="2b624-101">Stellt Satz von Aktionen, die geschrieben werden, in der SQL-basierte Syntax, die für eine ServiceBus.Messaging.BrokeredMessage ausgeführt wird</span><span class="sxs-lookup"><span data-stu-id="2b624-101">Represents set of actions written in SQL language-based syntax that is performed against a ServiceBus.Messaging.BrokeredMessage</span></span>
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
            <span data-ttu-id="2b624-102">Initialisiert eine neue Instanz der SqlRuleAction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2b624-102">Initializes a new instance of the SqlRuleAction class.</span></span>
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
        <param name="sqlExpression"><span data-ttu-id="2b624-103">SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="2b624-103">SQL expression.</span></span> <span data-ttu-id="2b624-104">z. B. MyProperty = 'ABC'</span><span class="sxs-lookup"><span data-stu-id="2b624-104">e.g. MyProperty='ABC'</span></span></param>
        <param name="compatibilityLevel"><span data-ttu-id="2b624-105">Diese Eigenschaft ist für eine spätere Verwendung vorgesehen.</span><span class="sxs-lookup"><span data-stu-id="2b624-105">This property is reserved for future use.</span></span> <span data-ttu-id="2b624-106">Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.</span><span class="sxs-lookup"><span data-stu-id="2b624-106">An integer value showing the compatibility level, currently hard-coded to 20.</span></span></param>
        <param name="requiresPreprocessing"><span data-ttu-id="2b624-107">Ein Wert, der angibt, ob die Aktion für eine vorverarbeitung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="2b624-107">Value that indicates whether the rule action requires preprocessing.</span></span></param>
        <summary>
            <span data-ttu-id="2b624-108">Initialisiert eine neue Instanz der SqlRuleAction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2b624-108">Initializes a new instance of the SqlRuleAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>