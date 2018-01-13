<Type Name="MultiShardPartialReadException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException">
  <TypeSignature Language="C#" Value="public class MultiShardPartialReadException : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardPartialReadException extends Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardPartialReadException&#xA;Inherits MultiShardException" />
  <TypeSignature Language="F#" Value="type MultiShardPartialReadException = class&#xA;    inherit MultiShardException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="610fc-101">Die <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> löst diese Ausnahme aus, wenn eine Ausnahme Lesen von Daten aus einer zugrunde liegenden Shards erreicht wurde.</span><span class="sxs-lookup"><span data-stu-id="610fc-101">The <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" /> throws this exception when an exception has been hit reading data from one of the underlying shards.</span></span> <span data-ttu-id="610fc-102">Dies gibt an, dass nicht alle Zeilen aus der entsprechenden shardingmechanismus erfolgreich abgerufen wurden.</span><span class="sxs-lookup"><span data-stu-id="610fc-102">This indicates that not all rows have been successfully retrieved from the targeted shard(s).</span></span> <span data-ttu-id="610fc-103">Benutzer können dann die Schritte erforderlich, um zu entscheiden, ob Sie die Abfrage erneut ausführen, oder zum Fortsetzen der Arbeit mit den Zeilen, die bereits abgerufen wurden.</span><span class="sxs-lookup"><span data-stu-id="610fc-103">Users can then take the steps necessary to decide whether to re-run the query, or whether to continue working with the rows that have already been retrieved.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="610fc-104">Diese Ausnahme wird nur mit der Richtlinie Teilergebnisse ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="610fc-104">This exception is only thrown with the partial results policy.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="610fc-105">Initialisiert eine neue Instanz der MultiShardPartialReadException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="610fc-105">Initializes a new instance of the MultiShardPartialReadException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="610fc-106">auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="610fc-106">specifices the message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="610fc-107">Initialisiert eine neue Instanz der Klasse MultiShardPartialReadException mit der angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="610fc-107">Initializes a new instance of the MultiShardPartialReadException class with the specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardPartialReadException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
            <span data-ttu-id="610fc-108">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> finden, die die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="610fc-108">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> see that holds the serialized object data about the exception being thrown.</span></span>
            </param>
        <param name="context">
            <span data-ttu-id="610fc-109">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="610fc-109">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span>
            </param>
        <summary>
            <span data-ttu-id="610fc-110">Initialisiert eine neue Instanz der MultiShardPartialReadException-Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="610fc-110">Initializes a new instance of the MultiShardPartialReadException class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="610fc-111">auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="610fc-111">specifices the message that explains the reason for the exception.</span></span></param>
        <param name="innerException"> <span data-ttu-id="610fc-112">Gibt an, die an den Shard aufgetretene Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="610fc-112">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="610fc-113">Initialisiert eine neue Instanz der Klasse MultiShardPartialReadException mit der angegebenen Fehlermeldung und der Verweis auf die innere Ausnahme, die die MultiShardPartialReadException verursacht.</span><span class="sxs-lookup"><span data-stu-id="610fc-113">Initializes a new instance of the MultiShardPartialReadException class with the specified error message and reference to the inner exception causing the MultiShardPartialReadException.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>