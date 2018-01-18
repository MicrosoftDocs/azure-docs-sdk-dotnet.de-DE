<Type Name="OracleSink" FullName="Microsoft.Azure.Management.DataFactories.Models.OracleSink">
  <TypeSignature Language="C#" Value="public class OracleSink : Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OracleSink extends Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.OracleSink" />
  <TypeSignature Language="VB.NET" Value="Public Class OracleSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type OracleSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a63e-101">Eine Oracle-Senke kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="9a63e-101">A copy activity Oracle sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OracleSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a63e-102">Initialisiert eine neue Instanz der OracleSink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a63e-102">Initializes a new instance of the OracleSink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OracleSink (int writeBatchSize, TimeSpan writeBatchTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 writeBatchSize, valuetype System.TimeSpan writeBatchTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.OracleSink.#ctor(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (writeBatchSize As Integer, writeBatchTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.OracleSink : int * TimeSpan -&gt; Microsoft.Azure.Management.DataFactories.Models.OracleSink" Usage="new Microsoft.Azure.Management.DataFactories.Models.OracleSink (writeBatchSize, writeBatchTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="writeBatchSize" Type="System.Int32" />
        <Parameter Name="writeBatchTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="writeBatchSize">To be added.</param>
        <param name="writeBatchTimeout">To be added.</param>
        <summary>
            <span data-ttu-id="9a63e-103">Initialisiert eine neue Instanz der OracleSink-Klasse mit erforderlichen Argumenten.</span><span class="sxs-lookup"><span data-stu-id="9a63e-103">Initializes a new instance of the OracleSink class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OracleWriterStoredProcedureName">
      <MemberSignature Language="C#" Value="public string OracleWriterStoredProcedureName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OracleWriterStoredProcedureName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OracleSink.OracleWriterStoredProcedureName" />
      <MemberSignature Language="VB.NET" Value="Public Property OracleWriterStoredProcedureName As String" />
      <MemberSignature Language="F#" Value="member this.OracleWriterStoredProcedureName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OracleSink.OracleWriterStoredProcedureName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a63e-104">Name der Oracle Writer gespeicherten Prozedur.</span><span class="sxs-lookup"><span data-stu-id="9a63e-104">Oracle writer stored procedure name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OracleWriterTableType">
      <MemberSignature Language="C#" Value="public string OracleWriterTableType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OracleWriterTableType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.OracleSink.OracleWriterTableType" />
      <MemberSignature Language="VB.NET" Value="Public Property OracleWriterTableType As String" />
      <MemberSignature Language="F#" Value="member this.OracleWriterTableType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.OracleSink.OracleWriterTableType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a63e-105">Tabellentyp für Oracle-Writer.</span><span class="sxs-lookup"><span data-stu-id="9a63e-105">Oracle writer table type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>