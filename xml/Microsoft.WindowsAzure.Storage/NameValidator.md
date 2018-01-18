<Type Name="NameValidator" FullName="Microsoft.WindowsAzure.Storage.NameValidator">
  <TypeSignature Language="C#" Value="public static class NameValidator" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NameValidator extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.NameValidator" />
  <TypeSignature Language="VB.NET" Value="Public Class NameValidator" />
  <TypeSignature Language="F#" Value="type NameValidator = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1f310-101">Stellt Hilfsprogramme zum Überprüfen von Ressourcennamen über die Microsoft Azure Storage Services bereit.</span><span class="sxs-lookup"><span data-stu-id="1f310-101">Provides helpers to validate resource names across the Microsoft Azure Storage Services.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ValidateBlobName">
      <MemberSignature Language="C#" Value="public static void ValidateBlobName (string blobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateBlobName(string blobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateBlobName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateBlobName (blobName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateBlobName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateBlobName blobName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobName"><span data-ttu-id="1f310-102">Eine Zeichenfolge, die den blobnamen zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="1f310-102">A string representing the blob name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-103">Überprüft, ob ein Blob-Name gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-103">Checks if a blob name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateContainerName">
      <MemberSignature Language="C#" Value="public static void ValidateContainerName (string containerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateContainerName(string containerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateContainerName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateContainerName (containerName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateContainerName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateContainerName containerName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="containerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerName"><span data-ttu-id="1f310-104">Eine Zeichenfolge, die den zu überprüfenden Containernamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-104">A string representing the container name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-105">Überprüft, ob ein Containername gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-105">Checks if a container name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateDirectoryName">
      <MemberSignature Language="C#" Value="public static void ValidateDirectoryName (string directoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateDirectoryName(string directoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateDirectoryName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateDirectoryName (directoryName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateDirectoryName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateDirectoryName directoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="directoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="directoryName"><span data-ttu-id="1f310-106">Eine Zeichenfolge, die den zu überprüfenden Verzeichnisnamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-106">A string representing the directory name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-107">Überprüft, ob ein Verzeichnisname gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-107">Checks if a directory name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateFileName">
      <MemberSignature Language="C#" Value="public static void ValidateFileName (string fileName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateFileName(string fileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateFileName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateFileName (fileName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateFileName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateFileName fileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fileName"><span data-ttu-id="1f310-108">Eine Zeichenfolge, die den zu überprüfenden Dateinamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-108">A string representing the file name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-109">Überprüft, ob ein Dateiname gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-109">Checks if a file name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateQueueName">
      <MemberSignature Language="C#" Value="public static void ValidateQueueName (string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateQueueName(string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateQueueName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateQueueName (queueName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateQueueName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateQueueName queueName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queueName"><span data-ttu-id="1f310-110">Eine Zeichenfolge, die den zu überprüfenden Warteschlangennamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-110">A string representing the queue name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-111">Überprüft, ob ein Warteschlangenname gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-111">Checks if a queue name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateShareName">
      <MemberSignature Language="C#" Value="public static void ValidateShareName (string shareName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateShareName(string shareName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateShareName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateShareName (shareName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateShareName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateShareName shareName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shareName"><span data-ttu-id="1f310-112">Eine Zeichenfolge, die den zu überprüfenden Freigabenamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-112">A string representing the share name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-113">Überprüft, ob ein Freigabename gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-113">Checks if a share name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateTableName">
      <MemberSignature Language="C#" Value="public static void ValidateTableName (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateTableName(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.NameValidator.ValidateTableName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateTableName (tableName As String)" />
      <MemberSignature Language="F#" Value="static member ValidateTableName : string -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.NameValidator.ValidateTableName tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="1f310-114">Eine Zeichenfolge, die den zu überprüfenden Tabellennamen darstellt.</span><span class="sxs-lookup"><span data-stu-id="1f310-114">A string representing the table name to validate.</span></span></param>
        <summary>
            <span data-ttu-id="1f310-115">Überprüft, ob ein Tabellenname gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1f310-115">Checks if a table name is valid.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>