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
    <summary><span data-ttu-id="7fe87-101">Stellt die Reihe von Aktionen, die in SQL-basierte Syntax, die für ausgeführt wird geschrieben eine <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="7fe87-101">Represents set of actions written in SQL language-based syntax that is performed against a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span></summary>
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
        <param name="sqlExpression"><span data-ttu-id="7fe87-102">Der SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-102">The SQL expression.</span></span></param>
        <summary><span data-ttu-id="7fe87-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> Klasse mit dem angegebenen SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> class with the specified SQL expression.</span></span></summary>
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
        <param name="sqlExpression"><span data-ttu-id="7fe87-104">Der SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-104">The SQL expression.</span></span></param>
        <param name="compatibilityLevel"><span data-ttu-id="7fe87-105">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="7fe87-105">Reserved for future use.</span></span> <span data-ttu-id="7fe87-106">Ein Ganzzahlwert, mit Kompatibilitätsgrad.</span><span class="sxs-lookup"><span data-stu-id="7fe87-106">An integer value showing compatibility level.</span></span> <span data-ttu-id="7fe87-107">Derzeit programmiert fest, dass 20.</span><span class="sxs-lookup"><span data-stu-id="7fe87-107">Currently hard-coded to 20.</span></span></param>
        <summary><span data-ttu-id="7fe87-108">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> -Klasse mit der angegebenen SQL-Ausdruck und Kompatibilität-Ebene.</span><span class="sxs-lookup"><span data-stu-id="7fe87-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> class with the specified SQL expression and compatibility level.</span></span></summary>
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
        <summary><span data-ttu-id="7fe87-109">Diese Eigenschaft ist für eine spätere Verwendung vorgesehen.</span><span class="sxs-lookup"><span data-stu-id="7fe87-109">This property is reserved for future use.</span></span> <span data-ttu-id="7fe87-110">Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.</span><span class="sxs-lookup"><span data-stu-id="7fe87-110">An integer value showing the compatibility level, currently hard-coded to 20.</span></span></summary>
        <value><span data-ttu-id="7fe87-111">Ein Ganzzahlwert, mit dem Kompatibilitätsgrad</span><span class="sxs-lookup"><span data-stu-id="7fe87-111">An integer value showing the compatibility level</span></span></value>
        <remarks><span data-ttu-id="7fe87-112">Diese Eigenschaft ist für eine spätere Verwendung vorgesehen.</span><span class="sxs-lookup"><span data-stu-id="7fe87-112">This property is reserved for future use.</span></span></remarks>
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
        <param name="message"><span data-ttu-id="7fe87-113">Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , der die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7fe87-113">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> to which the <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> will be applied.</span></span></param>
        <summary><span data-ttu-id="7fe87-114">Führt die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="7fe87-114">Executes the <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> object.</span></span></summary>
        <returns><span data-ttu-id="7fe87-115">Der verarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span><span class="sxs-lookup"><span data-stu-id="7fe87-115">The processed <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="7fe87-116">Wird ausgelöst, wenn der Vorgang für den aktuellen Status ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="7fe87-116">Thrown when the operation is not valid for the current state.</span></span></exception>
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
        <summary><span data-ttu-id="7fe87-117">Legt den Wert einer Regelaktion fest.</span><span class="sxs-lookup"><span data-stu-id="7fe87-117">Sets the value of a rule action.</span></span></summary>
        <value><span data-ttu-id="7fe87-118">Der Wert der Regelaktion.</span><span class="sxs-lookup"><span data-stu-id="7fe87-118">The value of a rule action.</span></span></value>
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
        <summary><span data-ttu-id="7fe87-119">Ruft die vorverarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-119">Gets the pre-processed <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> expression.</span></span></summary>
        <returns><span data-ttu-id="7fe87-120">Die vorverarbeitete <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-120">The preprocessed <see cref="T:Microsoft.ServiceBus.Messaging.RuleAction" /> expression.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException"><span data-ttu-id="7fe87-121">Wird ausgelöst, wenn die Regel Action-Anweisung ungültig ist oder übersteigt die maximal zulässige Anzahl von Aktionen.</span><span class="sxs-lookup"><span data-stu-id="7fe87-121">Thrown when the rule action statement is invalid or exceeds maximum allowed number of actions.</span></span></exception>
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
        <summary><span data-ttu-id="7fe87-122">Ruft einen Wert, der angibt, ob die <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> vorverarbeitung erfordert.</span><span class="sxs-lookup"><span data-stu-id="7fe87-122">Gets a value indicating whether the <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" /> requires preprocessing.</span></span></summary>
        <value><span data-ttu-id="7fe87-123">"true", wenn die SQL-Regel-Aktion erfordert vorverarbeitung; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="7fe87-123">true if the SQL rule action requires preprocessing; otherwise, false.</span></span> <span data-ttu-id="7fe87-124">Gibt zurzeit immer "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="7fe87-124">Currently always returns true.</span></span></value>
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
        <summary><span data-ttu-id="7fe87-125">Ruft den SQL-Ausdruck ab.</span><span class="sxs-lookup"><span data-stu-id="7fe87-125">Gets the SQL expression.</span></span></summary>
        <value><span data-ttu-id="7fe87-126">Der SQL-Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="7fe87-126">The SQL expression.</span></span></value>
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
        <summary><span data-ttu-id="7fe87-127">Gibt eine Zeichenfolgendarstellung <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</span><span class="sxs-lookup"><span data-stu-id="7fe87-127">Returns a string representation of <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</span></span></summary>
        <returns><span data-ttu-id="7fe87-128">Eine Zeichenfolgendarstellung von <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</span><span class="sxs-lookup"><span data-stu-id="7fe87-128">The string representation of <see cref="T:Microsoft.ServiceBus.Messaging.SqlRuleAction" />.</span></span></returns>
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
        <summary><span data-ttu-id="7fe87-129">Überprüft die SQL-Ausdruck für die SQL-92-Syntax und Regeln.</span><span class="sxs-lookup"><span data-stu-id="7fe87-129">Validates the SQL expression against the SQL 92 syntax and rules.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.RuleActionException"><span data-ttu-id="7fe87-130">Wird ausgelöst, wenn die Regel Action-Anweisung ungültig ist oder übersteigt die maximal zulässige Anzahl von Aktionen.</span><span class="sxs-lookup"><span data-stu-id="7fe87-130">Thrown when the rule action statement is invalid or exceeds maximum allowed number of actions.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>