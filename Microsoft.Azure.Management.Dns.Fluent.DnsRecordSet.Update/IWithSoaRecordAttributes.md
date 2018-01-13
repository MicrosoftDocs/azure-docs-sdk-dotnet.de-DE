<Type Name="IWithSoaRecordAttributes" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes">
  <TypeSignature Language="C#" Value="public interface IWithSoaRecordAttributes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSoaRecordAttributes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSoaRecordAttributes" />
  <TypeSignature Language="F#" Value="type IWithSoaRecordAttributes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="24f0f-101">Die Stufe der SOA Datensatzdefinition ermöglichen dessen Attribute aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="24f0f-101">The stage of the SOA record definition allowing to update its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithEmailServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithEmailServer (string emailServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithEmailServer(string emailServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithEmailServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithEmailServer (emailServerHostName As String) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithEmailServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithEmailServer emailServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="emailServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="emailServerHostName"><span data-ttu-id="24f0f-102">Die e-Mail-Server.</span><span class="sxs-lookup"><span data-stu-id="24f0f-102">The email server.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-103">Gibt den e-Mail-Server die SOA-Datensatz zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="24f0f-103">Specifies the email server associated with the SOA record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-104">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-104">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExpireTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithExpireTimeInSeconds (long expireTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithExpireTimeInSeconds(int64 expireTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithExpireTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpireTimeInSeconds (expireTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithExpireTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithExpireTimeInSeconds expireTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="expireTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="expireTimeInSeconds"><span data-ttu-id="24f0f-105">Die Zeit in Sekunden ablaufen.</span><span class="sxs-lookup"><span data-stu-id="24f0f-105">The expire time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-106">Gibt die Zeit in Sekunden, die ein sekundären Server die zwischengespeicherten Zonendatei z. B. behandeln, wenn der Name des primären Server nicht erreichbar ist.</span><span class="sxs-lookup"><span data-stu-id="24f0f-106">Specifies the time in seconds that a secondary name server will treat its cached zone file as valid when the primary name server cannot be contacted.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-107">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNegativeResponseCachingTimeToLiveInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithNegativeResponseCachingTimeToLiveInSeconds (long negativeCachingTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithNegativeResponseCachingTimeToLiveInSeconds(int64 negativeCachingTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithNegativeResponseCachingTimeToLiveInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNegativeResponseCachingTimeToLiveInSeconds (negativeCachingTimeToLive As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithNegativeResponseCachingTimeToLiveInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithNegativeResponseCachingTimeToLiveInSeconds negativeCachingTimeToLive" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="negativeCachingTimeToLive" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="negativeCachingTimeToLive"><span data-ttu-id="24f0f-108">Die Gültigkeitsdauer (TTL) für zwischengespeicherte negative Antwort.</span><span class="sxs-lookup"><span data-stu-id="24f0f-108">The TTL for cached negative response.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-109">Gibt die Zeit in Sekunden, dass alle Namenserver oder ein Resolver eine negative Antwort zwischengespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="24f0f-109">Specifies the time in seconds that any name server or resolver should cache a negative response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-110">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-110">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRefreshTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRefreshTimeInSeconds (long refreshTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRefreshTimeInSeconds(int64 refreshTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithRefreshTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRefreshTimeInSeconds (refreshTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithRefreshTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithRefreshTimeInSeconds refreshTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="refreshTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="refreshTimeInSeconds"><span data-ttu-id="24f0f-111">Die Aktualisierungszeit in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="24f0f-111">The refresh time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-112">Gibt Zeit in Sekunden, die ein sekundären Server warten soll, bevor Sie versuchen, wenden Sie sich an dem der primäre Namenserver für eine Zone Datei aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="24f0f-112">Specifies time in seconds that a secondary name server should wait before trying to contact the the primary name server for a zone file update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-113">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-113">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRetryTimeInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRetryTimeInSeconds (long refreshTimeInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithRetryTimeInSeconds(int64 refreshTimeInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithRetryTimeInSeconds(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetryTimeInSeconds (refreshTimeInSeconds As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithRetryTimeInSeconds : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithRetryTimeInSeconds refreshTimeInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="refreshTimeInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="refreshTimeInSeconds"><span data-ttu-id="24f0f-114">Die Wiederholungszeit in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="24f0f-114">The retry time in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-115">Gibt die Zeit in Sekunden, die ein sekundären Server warten soll, bevor Sie versuchen, wenden Sie sich an den primären Namenserver erneut nach einem fehlerhaftem Versuch, ein Update der Zone-Datei überprüfen.</span><span class="sxs-lookup"><span data-stu-id="24f0f-115">Specifies the time in seconds that a secondary name server should wait before trying to contact the primary name server again after a failed attempt to check for a zone file update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-116">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-116">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSerialNumber">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithSerialNumber (long serialNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord WithSerialNumber(int64 serialNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSoaRecordAttributes.WithSerialNumber(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSerialNumber (serialNumber As Long) As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member WithSerialNumber : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithSoaRecordAttributes.WithSerialNumber serialNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serialNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serialNumber"><span data-ttu-id="24f0f-117">Die Seriennummer.</span><span class="sxs-lookup"><span data-stu-id="24f0f-117">The serial number.</span></span></param>
        <summary>
            <span data-ttu-id="24f0f-118">Gibt die Seriennummer für die Zonendatei.</span><span class="sxs-lookup"><span data-stu-id="24f0f-118">Specifies the serial number for the zone file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="24f0f-119">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="24f0f-119">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>