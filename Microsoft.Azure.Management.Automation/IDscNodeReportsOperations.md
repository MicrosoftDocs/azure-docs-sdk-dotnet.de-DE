<Type Name="IDscNodeReportsOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeReportsOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeReportsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeReportsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeReportsOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeReportsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Der Dienstvorgang für Knoten Berichte.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;" Usage="iDscNodeReportsOperations.GetAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="nodeId">
            Der Dsc-Knoten-Id an.
            </param>
        <param name="reportId">
            Die Id des Berichts.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen der Dsc-Knoten-Berichtsdaten nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Get Berichtsvorgang für dsc-Knoten.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync (string resourceGroupName, string automationAccount, Guid nodeId, Guid reportId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt; GetContentAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Guid reportId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.GetContentAsync(System.String,System.String,System.Guid,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetContentAsync : string * string * Guid * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;" Usage="iDscNodeReportsOperations.GetContentAsync (resourceGroupName, automationAccount, nodeId, reportId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="reportId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="nodeId">
            Der Dsc-Knoten-Id an.
            </param>
        <param name="reportId">
            Die Id des Berichts.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen der Dsc-Knoten-Berichte nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für das Get Bericht Inhalt des Knotens.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeReportListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            der Name der Ressourcengruppe
            </param>
        <param name="automationAccount">
            Der Name des Automation-Konto.
            </param>
        <param name="parameters">
            Die Parameter für die Liste zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeReportsOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;" Usage="iDscNodeReportsOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeReportListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            Der Link zum Abrufen des nächsten Satzes von Elementen.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Abrufen der Liste der Dsc-Knoten-Bericht nach Knoten-Id und Bericht-Id an.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
        <returns>
            Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>