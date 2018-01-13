<Type Name="IUsageOperations" FullName="Microsoft.Azure.Management.Automation.IUsageOperations">
  <TypeSignature Language="C#" Value="public interface IUsageOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUsageOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IUsageOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUsageOperations" />
  <TypeSignature Language="F#" Value="type IUsageOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Dienstvorgang für Automation Verwendungen.  (siehe http://aka.ms/azureautomationsdk/usageoperations für Weitere Informationen)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.UsageListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.UsageListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IUsageOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.UsageListResponse&gt;" Usage="iUsageOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.UsageListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abgerufen Sie die Verwendung für die Konto-Id werden.  (siehe http://aka.ms/azureautomationsdk/usageoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für den Abrufvorgang für die Verwendung.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>