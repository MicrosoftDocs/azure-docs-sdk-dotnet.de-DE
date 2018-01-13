<Type Name="IWithDailyUsageQuota" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithDailyUsageQuota">
  <TypeSignature Language="C#" Value="public interface IWithDailyUsageQuota" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDailyUsageQuota" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithDailyUsageQuota" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDailyUsageQuota" />
  <TypeSignature Language="F#" Value="type IWithDailyUsageQuota = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein app-Funktionsdefinition, sodass täglich arbeitsspeicherauslastungs-Quote angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDailyUsageQuota">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithDailyUsageQuota (int quota);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithDailyUsageQuota(int32 quota) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithDailyUsageQuota.WithDailyUsageQuota(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDailyUsageQuota (quota As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDailyUsageQuota : int -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithDailyUsageQuota.WithDailyUsageQuota quota" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="quota" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="quota">Das tägliche nutzungskontingent.</param>
        <summary>
            Gibt den täglichen Obergrenze Daten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDailyUsageQuota">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithoutDailyUsageQuota ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate WithoutDailyUsageQuota() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithDailyUsageQuota.WithoutDailyUsageQuota" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDailyUsageQuota () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutDailyUsageQuota : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate" Usage="iWithDailyUsageQuota.WithoutDailyUsageQuota " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den täglichen Obergrenze Daten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>