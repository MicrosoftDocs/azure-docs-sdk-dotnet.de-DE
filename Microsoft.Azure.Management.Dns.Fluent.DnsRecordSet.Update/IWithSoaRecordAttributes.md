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
            Die Stufe der SOA Datensatzdefinition ermöglichen dessen Attribute aktualisieren.
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
        <param name="emailServerHostName">Die e-Mail-Server.</param>
        <summary>
            Gibt den e-Mail-Server die SOA-Datensatz zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="expireTimeInSeconds">Die Zeit in Sekunden ablaufen.</param>
        <summary>
            Gibt die Zeit in Sekunden, die ein sekundären Server die zwischengespeicherten Zonendatei z. B. behandeln, wenn der Name des primären Server nicht erreichbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="negativeCachingTimeToLive">Die Gültigkeitsdauer (TTL) für zwischengespeicherte negative Antwort.</param>
        <summary>
            Gibt die Zeit in Sekunden, dass alle Namenserver oder ein Resolver eine negative Antwort zwischengespeichert werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="refreshTimeInSeconds">Die Aktualisierungszeit in Sekunden.</param>
        <summary>
            Gibt Zeit in Sekunden, die ein sekundären Server warten soll, bevor Sie versuchen, wenden Sie sich an dem der primäre Namenserver für eine Zone Datei aktualisieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="refreshTimeInSeconds">Die Wiederholungszeit in Sekunden.</param>
        <summary>
            Gibt die Zeit in Sekunden, die ein sekundären Server warten soll, bevor Sie versuchen, wenden Sie sich an den primären Namenserver erneut nach einem fehlerhaftem Versuch, ein Update der Zone-Datei überprüfen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="serialNumber">Die Seriennummer.</param>
        <summary>
            Gibt die Seriennummer für die Zonendatei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>