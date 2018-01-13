<Type Name="IIscsiConnectionDetailsOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations">
  <TypeSignature Language="C#" Value="public interface IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIscsiConnectionDetailsOperations" />
  <TypeSignature Language="F#" Value="type IIscsiConnectionDetailsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Alle Vorgänge im Zusammenhang mit iSCSI-Verbindung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt; GetAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations.GetAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;" Usage="iIscsiConnectionDetailsOperations.GetAsync (deviceId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.IscsiConnectionResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            Die Geräte-Id für die der Aufruf erfolgt.
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden kann.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>To be added.</summary>
        <returns>
            Die Liste der Verbindungsdetails iSCSI-Antwort-Modell.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>