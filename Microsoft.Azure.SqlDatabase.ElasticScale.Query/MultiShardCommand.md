<Type Name="MultiShardCommand" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand">
  <TypeSignature Language="C#" Value="public sealed class MultiShardCommand : System.Data.Common.DbCommand" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MultiShardCommand extends System.Data.Common.DbCommand" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MultiShardCommand&#xA;Inherits DbCommand" />
  <TypeSignature Language="F#" Value="type MultiShardCommand = class&#xA;    inherit DbCommand" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Common.DbCommand</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.DesignerCategory("Code")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4e9a6-101">Ergänzt die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> mit ein Command-Objekt ähnelt der Triade von <see cref="T:System.Data.SqlClient.SqlConnection" />, <see cref="T:System.Data.SqlClient.SqlCommand" />, und <see cref="T:System.Data.SqlClient.SqlDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-101">Complements the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> with a command object similar to the triad of <see cref="T:System.Data.SqlClient.SqlConnection" />, <see cref="T:System.Data.SqlClient.SqlCommand" />, and <see cref="T:System.Data.SqlClient.SqlDataReader" />.</span></span> <span data-ttu-id="4e9a6-102">Die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> T-SQL-Command-Anweisung als Eingabe akzeptiert und führt den Befehl über die Auflistung von Shards, die gemäß dem entsprechenden <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-102">The <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> takes a T-SQL command statement as its input and executes the command across its collection of shards specified by its corresponding <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" />.</span></span>
            <span data-ttu-id="4e9a6-103">Die Ergebnisse der Verarbeitung der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> werden über die Execute-Methoden zur Verfügung gestellt und die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-103">The results from processing the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> are made available through the execute methods and the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public override void Cancel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Cancel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Cancel" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Cancel ()" />
      <MemberSignature Language="F#" Value="override this.Cancel : unit -&gt; unit" Usage="multiShardCommand.Cancel " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1031:DoNotCatchGeneralExceptionTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-104">Versucht, eine laufende abzubrechen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> und alle derzeit ausgeführte Arbeit, die auf die Shards für den Befehl ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-104">Attempts to cancel an in progress <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand" /> and any ongoing work that is performed at the shards on behalf of the command.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandText">
      <MemberSignature Language="C#" Value="public override string CommandText { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandText" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandText As String" />
      <MemberSignature Language="F#" Value="member this.CommandText : string with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandText" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Security", "CA2100:Review SQL queries for security vulnerabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-105">Ruft ab oder legt den Befehlstext zum dar, die den Satz von Shards ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-105">Gets or sets the command text to execute against the set of shards.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandTimeout">
      <MemberSignature Language="C#" Value="public override int CommandTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CommandTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.CommandTimeout : int with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-106">Die Zeit in Sekunden warten, bis der Befehl auf alle Shards ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-106">Time in seconds to wait for the command to be executed on ALL shards.</span></span>
            <span data-ttu-id="4e9a6-107">Der Wert 0 gibt an, zeitlich unbegrenzt warten.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-107">A value of 0 indicates no wait time limit.</span></span> <span data-ttu-id="4e9a6-108">Der Standardwert ist 300 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-108">The default is 300 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandTimeoutPerShard">
      <MemberSignature Language="C#" Value="public int CommandTimeoutPerShard { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 CommandTimeoutPerShard" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandTimeoutPerShard As Integer" />
      <MemberSignature Language="F#" Value="member this.CommandTimeoutPerShard : int with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-109">Diese Eigenschaft steuert das Zeitlimit für die Ausführung eines Befehls für einzelne Shards.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-109">This property controls the timeout for running a command against individual shards.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandType">
      <MemberSignature Language="C#" Value="public override System.Data.CommandType CommandType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Data.CommandType CommandType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property CommandType As CommandType" />
      <MemberSignature Language="F#" Value="member this.CommandType : System.Data.CommandType with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.CommandType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-110">Die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />des auszuführenden Befehls.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-110">The <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandType" />of the command to be executed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection Connection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection Connection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Connection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Connection As MultiShardConnection" />
      <MemberSignature Language="F#" Value="member this.Connection : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Connection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-111">Ruft die aktuelle Instanz von der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> mit diesem Befehl verbunden.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-111">Gets the current instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardConnection" /> associated with this command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDbParameter">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbParameter CreateDbParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Data.Common.DbParameter CreateDbParameter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateDbParameter" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDbParameter () As DbParameter" />
      <MemberSignature Language="F#" Value="override this.CreateDbParameter : unit -&gt; System.Data.Common.DbParameter" Usage="multiShardCommand.CreateDbParameter " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbParameter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-112">Erstellt eine Instanz der DbParameter</span><span class="sxs-lookup"><span data-stu-id="4e9a6-112">Creates an instance of the DbParameter</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateParameter">
      <MemberSignature Language="C#" Value="public static System.Data.SqlClient.SqlParameter CreateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Data.SqlClient.SqlParameter CreateParameter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateParameter" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateParameter () As SqlParameter" />
      <MemberSignature Language="F#" Value="static member CreateParameter : unit -&gt; System.Data.SqlClient.SqlParameter" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CreateParameter " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlParameter</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-113">Erstellt eine neue Instanz eines <see cref="T:System.Data.SqlClient.SqlParameter" />-Objekts.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-113">Creates a new instance of a <see cref="T:System.Data.SqlClient.SqlParameter" /> object.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbConnection">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbConnection DbConnection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbConnection DbConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbConnection" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Property DbConnection As DbConnection" />
      <MemberSignature Language="F#" Value="member this.DbConnection : System.Data.Common.DbConnection with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbConnection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-114">Verbindungen mit Shards.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-114">Connections to shards.</span></span> <span data-ttu-id="4e9a6-115">Nicht unterstützt/verfügbar gemacht werden, da Verbindungen intern von dieser Instanz verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="4e9a6-115">Not supported/exposed since connections are managed internally by this instance</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbParameterCollection">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbParameterCollection DbParameterCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbParameterCollection DbParameterCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbParameterCollection" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property DbParameterCollection As DbParameterCollection" />
      <MemberSignature Language="F#" Value="member this.DbParameterCollection : System.Data.Common.DbParameterCollection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbParameterCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-116">Ruft die Auflistung von "SqlParameter"</span><span class="sxs-lookup"><span data-stu-id="4e9a6-116">Gets the SqlParameter Collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DbTransaction">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbTransaction DbTransaction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.Common.DbTransaction DbTransaction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbTransaction" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Property DbTransaction As DbTransaction" />
      <MemberSignature Language="F#" Value="member this.DbTransaction : System.Data.Common.DbTransaction with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DbTransaction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbTransaction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-117">Diese Eigenschaft wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-117">This property is currently not supported.</span></span> <span data-ttu-id="4e9a6-118">Zugreifen auf die Eigenschaft führt zu einer Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-118">Accessing the property will result in an exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DesignTimeVisible">
      <MemberSignature Language="C#" Value="public override bool DesignTimeVisible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DesignTimeVisible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DesignTimeVisible" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property DesignTimeVisible As Boolean" />
      <MemberSignature Language="F#" Value="member this.DesignTimeVisible : bool with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.DesignTimeVisible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-119">Diese Eigenschaft wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-119">This property is currently not supported.</span></span> <span data-ttu-id="4e9a6-120">Zugreifen auf die Eigenschaft führt zu einer Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-120">Accessing the property will result in an exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="multiShardCommand.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1031:DoNotCatchGeneralExceptionTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"></param>
        <summary>
            <span data-ttu-id="4e9a6-121">Deaktiviert alle reservierten nicht verwalteten/verwalteten Ressourcen freizugeben</span><span class="sxs-lookup"><span data-stu-id="4e9a6-121">Dispose off any unmanaged/managed resources held</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteDbDataReader">
      <MemberSignature Language="C#" Value="protected override System.Data.Common.DbDataReader ExecuteDbDataReader (System.Data.CommandBehavior behavior);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Data.Common.DbDataReader ExecuteDbDataReader(valuetype System.Data.CommandBehavior behavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteDbDataReader(System.Data.CommandBehavior)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ExecuteDbDataReader (behavior As CommandBehavior) As DbDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteDbDataReader : System.Data.CommandBehavior -&gt; System.Data.Common.DbDataReader" Usage="multiShardCommand.ExecuteDbDataReader behavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.Common.DbDataReader</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
      </Parameters>
      <Docs>
        <param name="behavior">To be added.</param>
        <summary>
            - <span data-ttu-id="4e9a6-122">Führt die angegebene Abfrage für alle Shards und einen Reader, der Ergebnisse von ihnen umfasst zurück.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-122">Runs the given query against all shards and returns a reader that encompasses results from them.</span></span>
                - <span data-ttu-id="4e9a6-123">Verwendet die MultiShardExecutionPolicy.CompleteResults als die standardausführungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="4e9a6-123">Uses the MultiShardExecutionPolicy.CompleteResults as the default execution policy</span></span>
            - <span data-ttu-id="4e9a6-124">Enthält die $ShardName Pseudo-Spalte in den Ergebnissen <param name="behavior">Befehl zu verwendende Verhalten</param><returns>MultiShardDataReader-Instanz, die Ergebnisse von allen Shards umfasst</returns><exception cref="T:System.InvalidOperationException">Wenn CommandText null ist oder leere</exception><exception cref="T:System.InvalidOperationException">ist das Verhalten des Befehls nicht unterstützte (CloseConnection oder SingleResult oder SingleRow)</exception><exception cref="T:System.TimeoutException">Wenn vor dem Abschluss der CommandTimeout vergangen</exception></span><span class="sxs-lookup"><span data-stu-id="4e9a6-124">Includes the $ShardName pseudo column in the results <param name="behavior">Command behavior to use</param><returns>MultiShardDataReader instance that encompasses results from all shards</returns><exception cref="T:System.InvalidOperationException">If the commandText is null or empty</exception><exception cref="T:System.InvalidOperationException">If the command behavior is not supported (CloseConnection or SingleResult or SingleRow)</exception><exception cref="T:System.TimeoutException">If the CommandTimeout elapsed prior to completion</exception></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteDbDataReaderAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt; ExecuteDbDataReaderAsync (System.Data.CommandBehavior behavior, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class System.Data.Common.DbDataReader&gt; ExecuteDbDataReaderAsync(valuetype System.Data.CommandBehavior behavior, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteDbDataReaderAsync(System.Data.CommandBehavior,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteDbDataReaderAsync : System.Data.CommandBehavior * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt;" Usage="multiShardCommand.ExecuteDbDataReaderAsync (behavior, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Common.DbDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="behavior"><span data-ttu-id="4e9a6-125">Befehlsverhalten verwenden</span><span class="sxs-lookup"><span data-stu-id="4e9a6-125">Command behavior to use</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4e9a6-126">Abbruchtoken zum Abbrechen der Ausführung des Befehls</span><span class="sxs-lookup"><span data-stu-id="4e9a6-126">Cancellation token to cancel the command execution</span></span></param>
        <summary>
            - <span data-ttu-id="4e9a6-127">Die angegebene Abfrage für alle Shards asynchron ausgeführt wird</span><span class="sxs-lookup"><span data-stu-id="4e9a6-127">Executes the given query against all shards asynchronously</span></span>
            - <span data-ttu-id="4e9a6-128">Verwendet die MultiShardExecutionPolicy.CompleteResults als die standardausführungsrichtlinie</span><span class="sxs-lookup"><span data-stu-id="4e9a6-128">Uses the MultiShardExecutionPolicy.CompleteResults as the default execution policy</span></span>
            - <span data-ttu-id="4e9a6-129">Enthält die $ShardName Pseudo-Spalte in den Ergebnissen</span><span class="sxs-lookup"><span data-stu-id="4e9a6-129">Includes the $ShardName pseudo column in the results</span></span>
            </summary>
        <returns><span data-ttu-id="4e9a6-130">Eine Aufgabe mit einem TResult enthält, die Ergebnisse von allen Shards umfasst</span><span class="sxs-lookup"><span data-stu-id="4e9a6-130">A task with a TResult that encompasses results from all shards</span></span></returns>
        <remarks><span data-ttu-id="4e9a6-131">Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-131">Any exceptions during command execution are conveyed via the returned Task</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-132">Wenn die CommandText null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-132">If the commandText is null or empty</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteNonQuery">
      <MemberSignature Language="C#" Value="public override int ExecuteNonQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 ExecuteNonQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteNonQuery" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ExecuteNonQuery () As Integer" />
      <MemberSignature Language="F#" Value="override this.ExecuteNonQuery : unit -&gt; int" Usage="multiShardCommand.ExecuteNonQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-133">ExecuteNonQuery wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-133">ExecuteNonQuery is currently not supported</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteNonQueryAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;int&gt; ExecuteNonQueryAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ExecuteNonQueryAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteNonQueryAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteNonQueryAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="multiShardCommand.ExecuteNonQueryAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4e9a6-134">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="4e9a6-134">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="4e9a6-135">"Executenonqueryasync" wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-135">ExecuteNonQueryAsync is currently not supported</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReader" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReader () As MultiShardDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteReader : unit -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" Usage="multiShardCommand.ExecuteReader " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-136">ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-136">The ExecuteReader methods of the MultiShardCommand execute the given command statement on each shard and return the concatenation (i.e. UNION ALL) of the individual results from the shards in a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> <span data-ttu-id="4e9a6-137">Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-137">The execution policy regarding result completeness can be controlled by setting the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span> <span data-ttu-id="4e9a6-138">Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-138">The default execution policy is to return complete results.</span></span>
            </summary>
        <returns> <span data-ttu-id="4e9a6-139">die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-139">the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> instance with the overall concatenated result set.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-140">wird ausgelöst, wenn die CommandText null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-140">thrown if the commandText is null or empty</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4e9a6-141">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout verstrichene</span><span class="sxs-lookup"><span data-stu-id="4e9a6-141">thrown if the CommandTimeout elapsed prior to completion</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader (System.Data.CommandBehavior behavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader ExecuteReader(valuetype System.Data.CommandBehavior behavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReader(System.Data.CommandBehavior)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReader (behavior As CommandBehavior) As MultiShardDataReader" />
      <MemberSignature Language="F#" Value="override this.ExecuteReader : System.Data.CommandBehavior -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" Usage="multiShardCommand.ExecuteReader behavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
      </Parameters>
      <Docs>
        <param name="behavior"> <span data-ttu-id="4e9a6-142">Gibt an, die <see cref="T:System.Data.CommandBehavior" /> verwenden.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-142">specifies the <see cref="T:System.Data.CommandBehavior" /> to use.</span></span></param>
        <summary>
            <span data-ttu-id="4e9a6-143">ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-143">The ExecuteReader methods of the MultiShardCommand execute the given command statement on each shard and return the concatenation (i.e. UNION ALL) of the individual results from the shards in a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> <span data-ttu-id="4e9a6-144">Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-144">The execution policy regarding result completeness can be controlled by setting the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span> <span data-ttu-id="4e9a6-145">Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-145">The default execution policy is to return complete results.</span></span>
            </summary>
        <returns> <span data-ttu-id="4e9a6-146">die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-146">the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> instance with the overall concatenated result set.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-147">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-147">thrown if the commandText is null or empty, or if the specified command behavior is not supported such as CloseConnection or SingleRow.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4e9a6-148">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-148">thrown if the CommandTimeout elapsed prior to completion.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteReaderAsync () As Task(Of MultiShardDataReader)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-149">ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-149">The ExecuteReader methods of the MultiShardCommand execute the given command statement on each shard and return the concatenation (i.e. UNION ALL) of the individual results from the shards in a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> <span data-ttu-id="4e9a6-150">Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-150">The execution policy regarding result completeness can be controlled by setting the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span> <span data-ttu-id="4e9a6-151">Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-151">The default execution policy is to return complete results.</span></span>
            </summary>
        <returns> <span data-ttu-id="4e9a6-152">eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-152">a task warapping the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> instance with the overall concatenated result set.</span></span> </returns>
        <remarks><span data-ttu-id="4e9a6-153">Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-153">Any exceptions during command execution are conveyed via the returned Task.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-154">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-154">thrown if the commandText is null or empty, or if the specified command behavior is not supported such as CloseConnection or SingleRow.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4e9a6-155">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-155">thrown if the CommandTimeout elapsed prior to completion.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4e9a6-156">Abbruchtoken zum Abbrechen der Ausführung des Befehls</span><span class="sxs-lookup"><span data-stu-id="4e9a6-156">Cancellation token to cancel the command execution</span></span></param>
        <summary>
            <span data-ttu-id="4e9a6-157">ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-157">The ExecuteReader methods of the MultiShardCommand execute the given command statement on each shard and return the concatenation (i.e. UNION ALL) of the individual results from the shards in a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> <span data-ttu-id="4e9a6-158">Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-158">The execution policy regarding result completeness can be controlled by setting the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span> <span data-ttu-id="4e9a6-159">Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-159">The default execution policy is to return complete results.</span></span>
            </summary>
        <returns> <span data-ttu-id="4e9a6-160">eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-160">a task warapping the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> instance with the overall concatenated result set.</span></span> </returns>
        <remarks><span data-ttu-id="4e9a6-161">Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-161">Any exceptions during command execution are conveyed via the returned Task.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-162">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-162">thrown if the commandText is null or empty, or if the specified command behavior is not supported such as CloseConnection or SingleRow.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4e9a6-163">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-163">thrown if the CommandTimeout elapsed prior to completion.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteReaderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync (System.Data.CommandBehavior behavior, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt; ExecuteReaderAsync(valuetype System.Data.CommandBehavior behavior, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteReaderAsync(System.Data.CommandBehavior,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteReaderAsync : System.Data.CommandBehavior * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;" Usage="multiShardCommand.ExecuteReaderAsync (behavior, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="behavior" Type="System.Data.CommandBehavior" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="behavior"><span data-ttu-id="4e9a6-164">Befehlsverhalten verwenden</span><span class="sxs-lookup"><span data-stu-id="4e9a6-164">Command behavior to use</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="4e9a6-165">Abbruchtoken zum Abbrechen der Ausführung des Befehls</span><span class="sxs-lookup"><span data-stu-id="4e9a6-165">Cancellation token to cancel the command execution</span></span></param>
        <summary>
            <span data-ttu-id="4e9a6-166">ExecuteReader-Methoden von der MultiShardCommand führt die angegebene befehlsanweisung in jedem Shard und zurückgeben die Verkettung (d. h. UNION ALL) der einzelnen Ergebnisse aus den Shards in einem <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-166">The ExecuteReader methods of the MultiShardCommand execute the given command statement on each shard and return the concatenation (i.e. UNION ALL) of the individual results from the shards in a <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />.</span></span> <span data-ttu-id="4e9a6-167">Die Ausführungsrichtlinie bezüglich Ergebnis Vollständigkeit kann gesteuert werden, durch Festlegen der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-167">The execution policy regarding result completeness can be controlled by setting the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span> <span data-ttu-id="4e9a6-168">Die standardausführungsrichtlinie ist um vollständige Ergebnisse zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-168">The default execution policy is to return complete results.</span></span>
            </summary>
        <returns> <span data-ttu-id="4e9a6-169">eine Aufgabe Warapping der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> -Instanz mit der allgemeinen Resultset verkettet.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-169">a task warapping the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> instance with the overall concatenated result set.</span></span> </returns>
        <remarks><span data-ttu-id="4e9a6-170">Ausnahmen während der Ausführung des Befehls werden über die zurückgegebene Aufgabe weitergegeben.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-170">Any exceptions during command execution are conveyed via the returned Task.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4e9a6-171">wird ausgelöst, wenn CommandText null oder leer ist oder wenn das angegebene Befehlsverhalten z. B. CloseConnection oder SingleRow nicht unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-171">thrown if the commandText is null or empty, or if the specified command behavior is not supported such as CloseConnection or SingleRow.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4e9a6-172">wird ausgelöst, wenn vor dem Abschluss der CommandTimeout ist verstrichen.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-172">thrown if the CommandTimeout elapsed prior to completion.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScalar">
      <MemberSignature Language="C#" Value="public override object ExecuteScalar ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ExecuteScalar() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteScalar" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ExecuteScalar () As Object" />
      <MemberSignature Language="F#" Value="override this.ExecuteScalar : unit -&gt; obj" Usage="multiShardCommand.ExecuteScalar " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-173">ExecuteScalar wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-173">ExecuteScalar is currently not supported</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteScalarAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; ExecuteScalarAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; ExecuteScalarAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecuteScalarAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ExecuteScalarAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="multiShardCommand.ExecuteScalarAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="4e9a6-174">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="4e9a6-174">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="4e9a6-175">ExecuteScalarAsync wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-175">ExecuteScalarAsync is currently not supported</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions ExecutionOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions ExecutionOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionOptions As MultiShardExecutionOptions" />
      <MemberSignature Language="F#" Value="member this.ExecutionOptions : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-176">Ruft ab oder legt fest, die steuern, wie der Befehl ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-176">Gets or sets options that control how the command is executed.</span></span>
            <span data-ttu-id="4e9a6-177">Beispielsweise können Sie dies verwenden, um den Shard-Namen als eine zusätzliche Spalte in das Ergebnis einzuschließen.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-177">For instance, you can use this to include the shard name as an additional column into the result.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy ExecutionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy ExecutionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionPolicy As MultiShardExecutionPolicy" />
      <MemberSignature Language="F#" Value="member this.ExecutionPolicy : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ExecutionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-178">Die Ausführungsrichtlinie beim Ausführen von Befehlen auf Shards zu verwendende.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-178">The execution policy to use when executing commands against shards.</span></span> <span data-ttu-id="4e9a6-179">Durch diese Richtlinie können Benutzer steuern, ob die vollständigen Ergebnisse erforderlich sind, oder gibt an, ob Teilergebnisse zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-179">Through this policy, users can control whether complete results are required, or whether partial results are acceptable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Data.SqlClient.SqlParameterCollection Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Data.SqlClient.SqlParameterCollection Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As SqlParameterCollection" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Data.SqlClient.SqlParameterCollection" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.SqlClient.SqlParameterCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-180">Die <see cref="T:System.Data.SqlClient.SqlParameterCollection" /> mit diesem Befehl verbunden.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-180">The <see cref="T:System.Data.SqlClient.SqlParameterCollection" /> associated with this command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prepare">
      <MemberSignature Language="C#" Value="public override void Prepare ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Prepare() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.Prepare" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Prepare ()" />
      <MemberSignature Language="F#" Value="override this.Prepare : unit -&gt; unit" Usage="multiShardCommand.Prepare " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-181">Diese Methode wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-181">This method is currently not supported.</span></span> <span data-ttu-id="4e9a6-182">Aufrufen der Eigenschaft, führt zu einer Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-182">Invoking the property will result in an exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetCommandTimeout">
      <MemberSignature Language="C#" Value="public void ResetCommandTimeout ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetCommandTimeout() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ResetCommandTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetCommandTimeout ()" />
      <MemberSignature Language="F#" Value="member this.ResetCommandTimeout : unit -&gt; unit" Usage="multiShardCommand.ResetCommandTimeout " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-183">Setzt die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" /> Eigenschaft auf den Standardwert</span><span class="sxs-lookup"><span data-stu-id="4e9a6-183">Resets the <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeout" /> property to its default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetCommandTimeoutPerShard">
      <MemberSignature Language="C#" Value="public void ResetCommandTimeoutPerShard ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetCommandTimeoutPerShard() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ResetCommandTimeoutPerShard" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetCommandTimeoutPerShard ()" />
      <MemberSignature Language="F#" Value="member this.ResetCommandTimeoutPerShard : unit -&gt; unit" Usage="multiShardCommand.ResetCommandTimeoutPerShard " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-184">Setzt die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" /> Eigenschaft auf den Standardwert</span><span class="sxs-lookup"><span data-stu-id="4e9a6-184">Resets the <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.CommandTimeoutPerShard" /> property to its default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior RetryBehavior { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior RetryBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryBehavior As RetryBehavior" />
      <MemberSignature Language="F#" Value="member this.RetryBehavior : Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-185">Das Wiederholungsverhalten zum Erkennen von vorübergehenden Fehlern, die auftreten können, wenn eine Verbindung mit herstellen und Ausführen von Befehlen für einzelne Shards.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-185">The retry behavior for detecting transient faults that could occur when connecting to and executing commands against individual shards.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4e9a6-186">Die <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" /> ist die Standardeinstellung.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-186">The <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.RetryBehavior.DefaultRetryBehavior" /> is the default.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionBegan">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionBegan;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionBegan" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionBegan" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionBegan As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionBegan : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionBegan : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-187">Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard begonnen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-187">The event handler invoked when execution has begun on a given shard.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionCanceled">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionCanceled;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionCanceled" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionCanceled" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionCanceled As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionCanceled : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionCanceled : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-188">Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard abgebrochen wird, entweder explizit über die bereitgestellte <see cref="T:System.Threading.CancellationToken" /> oder implizit als Ergebnis der ausgewählten <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-188">The event handler invoked when execution on a given shard is canceled, either explicitly via the provided <see cref="T:System.Threading.CancellationToken" /> or implicitly as a result of the chosen <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardExecutionPolicy" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionFaulted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionFaulted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionFaulted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionFaulted" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionFaulted As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionFaulted : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionFaulted : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-189">Der Ereignishandler wird aufgerufen, wenn die Ausführung auf einem bestimmten Shard einen Fehler verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-189">The event handler invoked when execution on a given shard has faulted.</span></span> <span data-ttu-id="4e9a6-190">Dieser Handler wird nur aufgerufen, auf Ausnahmen für die Ausführung nicht Weitere daher wiederholt konnte die Ausnahme nicht-Transience oder aufgrund der ausgewählten <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-190">This handler is only invoked on exceptions for which execution could not be retried further as a result of the exception's non-transience or as a result of the chosen <see cref="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.RetryBehavior" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardExecutionSucceeded">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionSucceeded;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; ShardExecutionSucceeded" />
      <MemberSignature Language="DocId" Value="E:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.ShardExecutionSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event ShardExecutionSucceeded As EventHandler(Of ShardExecutionEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ShardExecutionSucceeded : EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " Usage="member this.ShardExecutionSucceeded : System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.Azure.SqlDatabase.ElasticScale.Query.ShardExecutionEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-191">Der Ereignishandler wird aufgerufen, wenn die Ausführung erfolgreich abgeschlossen wurde, auf einem bestimmten Shard oder seine Shard-spezifische <see cref="T:System.Data.IDataReader" /> zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-191">The event handler invoked when execution has successfully completed on a given shard or its shard-specific <see cref="T:System.Data.IDataReader" /> has been returned.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedRowSource">
      <MemberSignature Language="C#" Value="public override System.Data.UpdateRowSource UpdatedRowSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Data.UpdateRowSource UpdatedRowSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.UpdatedRowSource" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property UpdatedRowSource As UpdateRowSource" />
      <MemberSignature Language="F#" Value="member this.UpdatedRowSource : System.Data.UpdateRowSource with get, set" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardCommand.UpdatedRowSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Data.UpdateRowSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e9a6-192">Diese Eigenschaft wird derzeit nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-192">This property is currently not supported.</span></span> <span data-ttu-id="4e9a6-193">Zugreifen auf die Eigenschaft führt zu einer Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="4e9a6-193">Accessing the property will result in an exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>