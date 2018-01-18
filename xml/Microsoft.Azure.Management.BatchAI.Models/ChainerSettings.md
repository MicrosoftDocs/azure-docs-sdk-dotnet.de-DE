<Type Name="ChainerSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings">
  <TypeSignature Language="C#" Value="public class ChainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class ChainerSettings" />
  <TypeSignature Language="F#" Value="type ChainerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81c40-101">Gibt die Einstellungen für Chainer-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="81c40-101">Specifies the settings for Chainer job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChainerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81c40-102">Initialisiert eine neue Instanz der ChainerSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="81c40-102">Initializes a new instance of the ChainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChainerSettings (string pythonScriptFilePath, string pythonInterpreterPath = null, string commandLineArgs = null, Nullable&lt;int&gt; processCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs, valuetype System.Nullable`1&lt;int32&gt; processCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null, Optional processCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ChainerSettings : string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.ChainerSettings (pythonScriptFilePath, pythonInterpreterPath, commandLineArgs, processCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
        <Parameter Name="processCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath"><span data-ttu-id="81c40-103">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="81c40-103">The path and file name of the python script to execute the job.</span></span></param>
        <param name="pythonInterpreterPath"><span data-ttu-id="81c40-104">Der Pfad zur Python-Interpreter.</span><span class="sxs-lookup"><span data-stu-id="81c40-104">The path to python interpreter.</span></span></param>
        <param name="commandLineArgs"><span data-ttu-id="81c40-105">Befehlszeilenargumente, die an die Python-Skript übergeben werden muss</span><span class="sxs-lookup"><span data-stu-id="81c40-105">Command line arguments that needs to be passed to the python script</span></span></param>
        <param name="processCount"><span data-ttu-id="81c40-106">Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.</span><span class="sxs-lookup"><span data-stu-id="81c40-106">Number of processes parameter that is passed to MPI runtime.</span></span></param>
        <summary>
            <span data-ttu-id="81c40-107">Initialisiert eine neue Instanz der ChainerSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="81c40-107">Initializes a new instance of the ChainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.CommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81c40-108">Ruft ab oder legt ihn fest Befehlszeilenargumente, die an die Python-Skript übergeben werden muss</span><span class="sxs-lookup"><span data-stu-id="81c40-108">Gets or sets command line arguments that needs to be passed to the python script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.ProcessCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.ProcessCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81c40-109">Ruft ab oder legt die Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.</span><span class="sxs-lookup"><span data-stu-id="81c40-109">Gets or sets number of processes parameter that is passed to MPI runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="81c40-110">Der Standardwert für diese Eigenschaft ist gleich NodeCount-Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="81c40-110">The default value for this property is equal to nodeCount property</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonInterpreterPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonInterpreterPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81c40-111">Ruft ab oder legt den Pfad zu den Python-Interpreter fest.</span><span class="sxs-lookup"><span data-stu-id="81c40-111">Gets or sets the path to python interpreter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.PythonScriptFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonScriptFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81c40-112">Ruft ab oder legt den Pfad und den Namen der Python-Skript zum Ausführen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="81c40-112">Gets or sets the path and file name of the python script to execute the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ChainerSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="chainerSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="81c40-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="81c40-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="81c40-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="81c40-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>