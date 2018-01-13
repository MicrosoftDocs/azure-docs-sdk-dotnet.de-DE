<Type Name="CNTKsettings" FullName="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings">
  <TypeSignature Language="C#" Value="public class CNTKsettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CNTKsettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CNTKsettings" />
  <TypeSignature Language="F#" Value="type CNTKsettings = class" />
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
            Gibt die Einstellungen für den Auftrag CNTK (d. h. Microsoft Cognitive Toolkit).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CNTKsettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CNTKsettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CNTKsettings (string languageType = null, string configFilePath = null, string pythonScriptFilePath = null, string pythonInterpreterPath = null, string commandLineArgs = null, Nullable&lt;int&gt; processCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string languageType, string configFilePath, string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs, valuetype System.Nullable`1&lt;int32&gt; processCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional languageType As String = null, Optional configFilePath As String = null, Optional pythonScriptFilePath As String = null, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null, Optional processCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.CNTKsettings : string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.CNTKsettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.CNTKsettings (languageType, configFilePath, pythonScriptFilePath, pythonInterpreterPath, commandLineArgs, processCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="languageType" Type="System.String" />
        <Parameter Name="configFilePath" Type="System.String" />
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
        <Parameter Name="processCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="languageType">Gibt an, welche Sprache zum Starten von Auftrag CNTK (d. h. Microsoft Cognitive Toolkit) verwendet werden soll.</param>
        <param name="configFilePath">Gibt den Pfad der Datei "App.config".</param>
        <param name="pythonScriptFilePath">Der Pfad und Dateiname der Name des Python-Skript zum Ausführen des Auftrags.</param>
        <param name="pythonInterpreterPath">Der Pfad zur Python-Interpreter.</param>
        <param name="commandLineArgs">Befehlszeilenargumente, die an die Python-Skript oder CNTK.exe übergeben werden muss.</param>
        <param name="processCount">Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.</param>
        <summary>
            Initialisiert eine neue Instanz der CNTKsettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.CommandLineArgs" />
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
            Ruft ab oder legt Befehlszeilenargumente, die an die Python-Skript oder CNTK.exe übergeben werden muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigFilePath">
      <MemberSignature Language="C#" Value="public string ConfigFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.ConfigFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigFilePath As String" />
      <MemberSignature Language="F#" Value="member this.ConfigFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.ConfigFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Pfad der Datei "App.config".
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn die LanguageType "BrainScript" ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LanguageType">
      <MemberSignature Language="C#" Value="public string LanguageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LanguageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.LanguageType" />
      <MemberSignature Language="VB.NET" Value="Public Property LanguageType As String" />
      <MemberSignature Language="F#" Value="member this.LanguageType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.LanguageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="languageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, welche Sprache zum Starten von Auftrag CNTK (d. h. Microsoft Cognitive Toolkit) verwendet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Gültige Werte sind "BrainScript" oder "Python".
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.ProcessCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.ProcessCount" />
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
            Ruft ab oder legt die Anzahl der Prozesse-Parameter, um MPI-Runtime übergeben wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert für diese Eigenschaft ist gleich NodeCount-Eigenschaft
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.PythonInterpreterPath" />
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
            Ruft ab oder legt den Pfad zu den Python-Interpreter fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn die LanguageType "Python" ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings.PythonScriptFilePath" />
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
            Ruft ab oder legt den Pfad und den Namen der Python-Skript zum Ausführen des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft kann nur angegeben werden, wenn die LanguageType "Python" ist.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>