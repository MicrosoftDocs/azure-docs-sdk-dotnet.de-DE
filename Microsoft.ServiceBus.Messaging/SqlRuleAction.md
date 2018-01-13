<Type Name="SqlRuleAction" FullName="Microsoft.ServiceBus.Messaging.SqlRuleAction">
  <TypeSignature Language="C#" Value="public sealed class SqlRuleAction : Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SqlRuleAction extends Microsoft.ServiceBus.Messaging.RuleAction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SqlRuleAction&#xA;Inherits RuleAction" />
  <TypeSignature Language="F#" Value="type SqlRuleAction = class&#xA;    inherit RuleAction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.RuleAction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SqlRuleAction", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die Reihe von Aktionen, die in SQL-basierte Syntax, die für ausgeführt wird geschrieben eine <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SqlRuleAction : string -&gt; Microsoft.ServiceBus.Messaging.SqlRuleAction" Usage="new Microsoft.ServiceBus.Messaging.SqlRuleAction sqlExpression" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">Der SQL-Ausdruck.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> Klasse mit dem angegebenen SQL-Ausdruck.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SqlRuleAction (string sqlExpression, int compatibilityLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression, int32 compatibilityLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (sqlExpression As String, compatibilityLevel As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SqlRuleAction : string * int -&gt; Microsoft.ServiceBus.Messaging.SqlRuleAction" Usage="new Microsoft.ServiceBus.Messaging.SqlRuleAction (sqlExpression, compatibilityLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">Der SQL-Ausdruck.</param>
        <param name="compatibilityLevel">Für zukünftige Verwendung reserviert. Ein Ganzzahlwert, mit Kompatibilitätsgrad. Derzeit programmiert fest, dass 20.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> -Klasse mit der angegebenen SQL-Ausdruck und Kompatibilität-Ebene.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public int CompatibilityLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompatibilityLevel As Integer" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : int" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="CompatibilityLevel", Order=65538)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Diese Eigenschaft ist für eine spätere Verwendung vorgesehen. Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.</summary>
        <value>Ein Ganzzahlwert, mit dem Kompatibilitätsgrad</value>
        <remarks>Diese Eigenschaft ist für eine spätere Verwendung vorgesehen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.BrokeredMessage Execute (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Execute(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Execute(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Execute (message As BrokeredMessage) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="override this.Execute : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="sqlRuleAction.Execute message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , der die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> angewendet werden.</param>
        <summary>Führt die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> Objekt.</summary>
        <returns>Der verarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn der Vorgang für den aktuellen Status ungültig ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Legt den Wert einer Regelaktion fest.</summary>
        <value>Der Wert der Regelaktion.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Preprocess">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.Messaging.RuleAction Preprocess ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.Messaging.RuleAction Preprocess() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Preprocess" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Preprocess () As RuleAction" />
      <MemberSignature Language="F#" Value="override this.Preprocess : unit -&gt; Microsoft.ServiceBus.Messaging.RuleAction" Usage="sqlRuleAction.Preprocess " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RuleAction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die vorverarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Ausdruck.</summary>
        <returns>Die vorverarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Ausdruck.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException">Wird ausgelöst, wenn die Regel Action-Anweisung ungültig ist oder übersteigt die maximal zulässige Anzahl von Aktionen.</exception>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public override bool RequiresPreprocessing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RequiresPreprocessing As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : bool" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der angibt, ob die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> vorverarbeitung erfordert.</summary>
        <value>"true", wenn die SQL-Regel-Aktion erfordert vorverarbeitung; andernfalls "false". Gibt zurzeit immer "true" zurück.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SqlRuleAction.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string" Usage="Microsoft.ServiceBus.Messaging.SqlRuleAction.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=true, Name="SqlExpression", Order=65537)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den SQL-Ausdruck ab.</summary>
        <value>Der SQL-Ausdruck.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="sqlRuleAction.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt eine Zeichenfolgendarstellung <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</summary>
        <returns>Eine Zeichenfolgendarstellung von <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SqlRuleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="sqlRuleAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Überprüft die SQL-Ausdruck für die SQL-92-Syntax und Regeln.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException">Wird ausgelöst, wenn die Regel Action-Anweisung ungültig ist oder übersteigt die maximal zulässige Anzahl von Aktionen.</exception>
      </Docs>
    </Member>
  </Members>
</Type>