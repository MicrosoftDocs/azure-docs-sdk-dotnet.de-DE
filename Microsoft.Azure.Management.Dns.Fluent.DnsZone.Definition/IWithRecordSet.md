<Type Name="IWithRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet">
  <TypeSignature Language="C#" Value="public interface IWithRecordSet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRecordSet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRecordSet" />
  <TypeSignature Language="F#" Value="type IWithRecordSet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase des DNS-zone Definition Ressourceneintragssatz angeben können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAaaaRecordSet (name As String) As IAaaaRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Name der AAAA-Eintrag festgelegt.</param>
        <summary>
            Gibt die Definition einer AAAA-Ressourceneintragssatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die Konfiguration für den AAAA-Ressourceneintragssatz darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineARecordSet (name As String) As IARecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Name der A-Eintrag festgelegt.</param>
        <summary>
            Gibt die Definition einer Datensatzgruppe ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Legen Sie die Phase, die Konfiguration für den A-Eintrag darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineCNameRecordSet (name As String) As ICNameRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineMXRecordSet (name As String) As IMXRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des MX-Eintrags festgelegt.</param>
        <summary>
            Gibt einen MX-Ressourceneintragssatz Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Legen Sie die Phase, die Konfiguration für den MX-Eintrag darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNSRecordSet (name As String) As INSRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Name des NS Ressourceneintragssatz.</param>
        <summary>
            Gibt eine Datensatzgruppe NS-Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, Konfiguration für die Datensatzgruppe NS darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefinePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefinePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefinePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefinePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePtrRecordSet (name As String) As IPtrRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefinePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Name der PTR-Eintrag festgelegt.</param>
        <summary>
            Gibt einen PTR-Ressourceneintragssatz Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die Konfiguration für den PTR-Ressourceneintragssatz darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSrvRecordSet (name As String) As ISrvRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des SRV-Eintrags festgelegt.</param>
        <summary>
            Gibt die Definition einer SRV-Datensatzgruppe an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die Konfiguration für den SRV-Ressourceneintragssatz darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineTxtRecordSet (name As String) As ITxtRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der TXT-Eintrag festgelegt.</param>
        <summary>
            Gibt einen TXT-Ressourceneintragssatz Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Legen Sie die Phase, die Konfiguration für den TXT-Eintrag darstellt.</return>
      </Docs>
    </Member>
    <Member MemberName="WithCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate WithCNameRecordSet (string name, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate WithCNameRecordSet(string name, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.WithCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCNameRecordSet (name As String, alias As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate" Usage="iWithRecordSet.WithCNameRecordSet (name, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des CNAME-Eintrags festgelegt.</param>
        <param name="alias">Der Alias für den CNAME-Datensatz.</param>
        <summary>
            Gibt einen CNAME-Ressourceneintragssatz Definition.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der DNS-Zone Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>