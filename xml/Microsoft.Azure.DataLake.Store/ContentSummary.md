<Type Name="ContentSummary" FullName="Microsoft.Azure.DataLake.Store.ContentSummary">
  <TypeSignature Language="C#" Value="public class ContentSummary" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContentSummary extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.ContentSummary" />
  <TypeSignature Language="VB.NET" Value="Public Class ContentSummary" />
  <TypeSignature Language="F#" Value="type ContentSummary = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81572-101">Kapselt Verzeichnisanzahl gesamt, Anzahl der Dateien, verbrauchte Speicherplatz</span><span class="sxs-lookup"><span data-stu-id="81572-101">Encapsulates total directory count, file count, space consumed</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContentSummary (long directoryCnt, long fileCnt, long length, long spaceConsumed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 directoryCnt, int64 fileCnt, int64 length, int64 spaceConsumed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.ContentSummary.#ctor(System.Int64,System.Int64,System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directoryCnt As Long, fileCnt As Long, length As Long, spaceConsumed As Long)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.ContentSummary : int64 * int64 * int64 * int64 -&gt; Microsoft.Azure.DataLake.Store.ContentSummary" Usage="new Microsoft.Azure.DataLake.Store.ContentSummary (directoryCnt, fileCnt, length, spaceConsumed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directoryCnt" Type="System.Int64" />
        <Parameter Name="fileCnt" Type="System.Int64" />
        <Parameter Name="length" Type="System.Int64" />
        <Parameter Name="spaceConsumed" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="directoryCnt"><span data-ttu-id="81572-102">Verzeichnisanzahl</span><span class="sxs-lookup"><span data-stu-id="81572-102">Directory count</span></span></param>
        <param name="fileCnt"><span data-ttu-id="81572-103">Dateianzahl</span><span class="sxs-lookup"><span data-stu-id="81572-103">File count</span></span></param>
        <param name="length"><span data-ttu-id="81572-104">Größe</span><span class="sxs-lookup"><span data-stu-id="81572-104">Size</span></span></param>
        <param name="spaceConsumed"><span data-ttu-id="81572-105">Gesamtgröße</span><span class="sxs-lookup"><span data-stu-id="81572-105">Total size</span></span></param>
        <summary>
            <span data-ttu-id="81572-106">Erstellt die Instanz des contentsummary</span><span class="sxs-lookup"><span data-stu-id="81572-106">Creates instance of contentsummary</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DirectoryCount">
      <MemberSignature Language="C#" Value="public long DirectoryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DirectoryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.ContentSummary.DirectoryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DirectoryCount As Long" />
      <MemberSignature Language="F#" Value="member this.DirectoryCount : int64" Usage="Microsoft.Azure.DataLake.Store.ContentSummary.DirectoryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81572-107">Verzeichnisanzahl gesamt</span><span class="sxs-lookup"><span data-stu-id="81572-107">Total directory count</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileCount">
      <MemberSignature Language="C#" Value="public long FileCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FileCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.ContentSummary.FileCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileCount As Long" />
      <MemberSignature Language="F#" Value="member this.FileCount : int64" Usage="Microsoft.Azure.DataLake.Store.ContentSummary.FileCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81572-108">Anzahl von Dateien insgesamt</span><span class="sxs-lookup"><span data-stu-id="81572-108">Total file count</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Length">
      <MemberSignature Language="C#" Value="public long Length { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Length" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.ContentSummary.Length" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Length As Long" />
      <MemberSignature Language="F#" Value="member this.Length : int64" Usage="Microsoft.Azure.DataLake.Store.ContentSummary.Length" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81572-109">Größe der Auslagerungsdatei insgesamt</span><span class="sxs-lookup"><span data-stu-id="81572-109">Total file sizes</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpaceConsumed">
      <MemberSignature Language="C#" Value="public long SpaceConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SpaceConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.ContentSummary.SpaceConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SpaceConsumed As Long" />
      <MemberSignature Language="F#" Value="member this.SpaceConsumed : int64" Usage="Microsoft.Azure.DataLake.Store.ContentSummary.SpaceConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="81572-110">Insgesamt belegten Speicherplatz</span><span class="sxs-lookup"><span data-stu-id="81572-110">Total space consumed</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>