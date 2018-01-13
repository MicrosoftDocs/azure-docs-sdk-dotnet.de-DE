<Type Name="SqlRuleAction" FullName="Microsoft.Azure.ServiceBus.SqlRuleAction">
  <TypeSignature Language="C#" Value="public sealed class SqlRuleAction : Microsoft.Azure.ServiceBus.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlRuleAction extends Microsoft.Azure.ServiceBus.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SqlRuleAction" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlRuleAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type SqlRuleAction = class&#xA;    inherit RuleAction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.RuleAction</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt die Reihe von Aktionen, die in SQL-basierte Syntax, die für ausgeführt wird geschrieben eine <see cref="T:Microsoft.Azure.ServiceBus.Message" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlRuleAction.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SqlRuleAction : string -&gt; Microsoft.Azure.ServiceBus.SqlRuleAction" Usage="new Microsoft.Azure.ServiceBus.SqlRuleAction sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">Der SQL-Ausdruck.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.ServiceBus.SqlRuleAction" /> Klasse mit dem angegebenen SQL-Ausdruck.
            </summary>
        <remarks>Maximal zulässige Länge von Sql-Ausdruck ist 1024 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlRuleAction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.Azure.ServiceBus.SqlRuleAction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legt den Wert einer Regelaktion fest.
            </summary>
        <value>Der Wert der Regelaktion.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SqlRuleAction.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.Azure.ServiceBus.SqlRuleAction.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den SQL-Ausdruck ab.
            </summary>
        <value>Der SQL-Ausdruck.</value>
        <remarks>Maximal zulässige Länge von Sql-Ausdruck ist 1024 Zeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SqlRuleAction.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlRuleAction.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt eine Zeichenfolgendarstellung <see cref="T:Microsoft.Azure.ServiceBus.SqlRuleAction" />.
            </summary>
        <returns>Eine Zeichenfolgendarstellung von <see cref="T:Microsoft.Azure.ServiceBus.SqlRuleAction" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>