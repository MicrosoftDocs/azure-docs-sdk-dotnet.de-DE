<Type Name="GetBackupResponse" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse">
  <TypeSignature Language="C#" Value="public class GetBackupResponse : Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GetBackupResponse extends Microsoft.Azure.AzureOperationResponse" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse" />
  <TypeSignature Language="VB.NET" Value="Public Class GetBackupResponse&#xA;Inherits AzureOperationResponse" />
  <TypeSignature Language="F#" Value="type GetBackupResponse = class&#xA;    inherit AzureOperationResponse" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.AzureOperationResponse</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9d595-101">Das Antwort-Modell für die Liste der Sicherungssätze.</span><span class="sxs-lookup"><span data-stu-id="9d595-101">The response model for the list of BackupSets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GetBackupResponse ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9d595-102">Initialisiert eine neue Instanz der GetBackupResponse-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9d595-102">Initializes a new instance of the GetBackupResponse class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSetsList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.Backup&gt; BackupSetsList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.Backup&gt; BackupSetsList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.BackupSetsList" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSetsList As IList(Of Backup)" />
      <MemberSignature Language="F#" Value="member this.BackupSetsList : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.Backup&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.BackupSetsList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.Backup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d595-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9d595-103">Required.</span></span> <span data-ttu-id="9d595-104">Liste der Sicherungssätze, die zurückgegeben werden</span><span class="sxs-lookup"><span data-stu-id="9d595-104">List of BackupSets to be returned</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextPageStartIdentifier">
      <MemberSignature Language="C#" Value="public string NextPageStartIdentifier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextPageStartIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.NextPageStartIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public Property NextPageStartIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.NextPageStartIdentifier : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.NextPageStartIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d595-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9d595-105">Required.</span></span> <span data-ttu-id="9d595-106">Skip-Bezeichner, der zur nächsten Seite wechseln</span><span class="sxs-lookup"><span data-stu-id="9d595-106">Skip identifier to go to next page</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextPageUri">
      <MemberSignature Language="C#" Value="public Uri NextPageUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri NextPageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.NextPageUri" />
      <MemberSignature Language="VB.NET" Value="Public Property NextPageUri As Uri" />
      <MemberSignature Language="F#" Value="member this.NextPageUri : Uri with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.NextPageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d595-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9d595-107">Required.</span></span> <span data-ttu-id="9d595-108">URI-Link, um zur nächsten Ergebnisseite zu wechseln</span><span class="sxs-lookup"><span data-stu-id="9d595-108">Uri link to go to the next result page</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalBackupCount">
      <MemberSignature Language="C#" Value="public long TotalBackupCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalBackupCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.TotalBackupCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalBackupCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalBackupCount : int64 with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse.TotalBackupCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9d595-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9d595-109">Required.</span></span> <span data-ttu-id="9d595-110">Gesamtzahl der Sicherungssätze in das Ergebnis</span><span class="sxs-lookup"><span data-stu-id="9d595-110">Total number of Backupsets in the result</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>