<Type Name="ExeHostEntryPointDescription" FullName="System.Fabric.Description.ExeHostEntryPointDescription">
  <TypeSignature Language="C#" Value="public sealed class ExeHostEntryPointDescription : System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExeHostEntryPointDescription extends System.Fabric.Description.EntryPointDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ExeHostEntryPointDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExeHostEntryPointDescription&#xA;Inherits EntryPointDescription" />
  <TypeSignature Language="F#" Value="type ExeHostEntryPointDescription = class&#xA;    inherit EntryPointDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.EntryPointDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="db3b2-101">Enthält Informationen zu den ausführbaren Einstiegspunkt.</span><span class="sxs-lookup"><span data-stu-id="db3b2-101">Provides information about the executable entry point.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public string Arguments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Arguments" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Arguments As String" />
      <MemberSignature Language="F#" Value="member this.Arguments : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-102">Ruft ab oder legt die Argumente an die ausführbare Datei im Dienstmanifest gemäß.</span><span class="sxs-lookup"><span data-stu-id="db3b2-102">Gets or sets the arguments passed to the executable as specified in the service manifest.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-103">Die Argumente, die entsprechend den Angaben in das Dienstmanifest an die ausführbare Datei übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="db3b2-103">The arguments passed to the executable as specified in the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionEnabled">
      <MemberSignature Language="C#" Value="public bool ConsoleRedirectionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ConsoleRedirectionEnabled" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionEnabled : bool" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-104">Ruft ab oder legt einen Wert, der angibt, ob aktiviert oder deaktiviert die Umleitung der Konsole für ausführbare Dateien fest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-104">Gets or sets a value that indicates whether to enable or disable console redirection for executables.</span></span> <span data-ttu-id="db3b2-105">Die Standardeinstellung lautet <languageKeyword>false</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="db3b2-105">Default is <languageKeyword>false</languageKeyword>.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="db3b2-106"><languageKeyword>"true"</languageKeyword> So aktivieren Sie die Umleitung der Konsole für ausführbare Dateien; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="db3b2-106"><languageKeyword>true</languageKeyword> to enable console redirection for executables; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileMaxSizeInKb">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileMaxSizeInKb { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileMaxSizeInKb As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileMaxSizeInKb : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileMaxSizeInKb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-107">Ruft ab oder legt die maximale Größe in KB für Umleitung Konsolendatei fest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-107">Gets or sets the maximum size in KB for console redirection file.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-108">Die maximale Größe in KB für Umleitung Konsolendatei.</span><span class="sxs-lookup"><span data-stu-id="db3b2-108">The maximum size in KB for console redirection file.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsoleRedirectionFileRetentionCount">
      <MemberSignature Language="C#" Value="public long ConsoleRedirectionFileRetentionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsoleRedirectionFileRetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.ConsoleRedirectionFileRetentionCount : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.ConsoleRedirectionFileRetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-109">Ruft ab oder legt die maximale Anzahl von Dateien für die Umleitung der Konsole vor dem Überschreiben von Inhalten in zirkulär.</span><span class="sxs-lookup"><span data-stu-id="db3b2-109">Gets or sets the maximum number of files used for console redirection before overwriting content in circular way.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-110">Die maximale Anzahl von Dateien, die für die Umleitung der Konsole vor dem Überschreiben von Inhalt in einer kreisförmigen Weise verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="db3b2-110">The maximum number of files used for console redirection before overwriting content in circular way.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeriodicInterval">
      <MemberSignature Language="C#" Value="public long PeriodicInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PeriodicInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PeriodicInterval As Long" />
      <MemberSignature Language="F#" Value="member this.PeriodicInterval : int64" Usage="System.Fabric.Description.ExeHostEntryPointDescription.PeriodicInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-111">Ruft ab oder legt den Zeitraum fest, wenn die ausführbare Datei muss in regelmäßigen Abständen aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="db3b2-111">Gets or sets the time period, if executable needs to be activated periodically.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-112">Der Zeitraum muss die ausführbare Datei in regelmäßigen Abständen aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="db3b2-112">The time period the executable needs to be activated periodically.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Program">
      <MemberSignature Language="C#" Value="public string Program { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Program" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.Program" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Program As String" />
      <MemberSignature Language="F#" Value="member this.Program : string" Usage="System.Fabric.Description.ExeHostEntryPointDescription.Program" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-113">Ruft ab oder legt den Namen der ausführbaren Datei entsprechend den Angaben in das Manifest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-113">Gets or sets the executable name as specified in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-114">Namen der ausführbaren Datei entsprechend den Angaben in das Manifest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-114">The executable name as specified in the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ExeHostEntryPointDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="exeHostEntryPointDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-115">Ruft die Zeichenfolgendarstellung dieser Einstiegspunkt ab.</span><span class="sxs-lookup"><span data-stu-id="db3b2-115">Gets the string representation of this entry point.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="db3b2-116">Die Zeichenfolgendarstellung dieser Einstiegspunkt.</span><span class="sxs-lookup"><span data-stu-id="db3b2-116">The string representation of this entry point.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkingFolder">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ExeHostWorkingFolder WorkingFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ExeHostWorkingFolder WorkingFolder" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkingFolder As ExeHostWorkingFolder" />
      <MemberSignature Language="F#" Value="member this.WorkingFolder : System.Fabric.Description.ExeHostWorkingFolder" Usage="System.Fabric.Description.ExeHostEntryPointDescription.WorkingFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ExeHostWorkingFolder</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db3b2-117">Abrufen oder festlegen den Arbeitsordner für die ausführbare Datei entsprechend den Angaben in das Manifest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-117">Gets or sets the working folder for the executable as specified in the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="db3b2-118">Der Arbeitsordner für die ausführbare Datei entsprechend den Angaben in das Manifest.</span><span class="sxs-lookup"><span data-stu-id="db3b2-118">The working folder for the executable as specified in the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>