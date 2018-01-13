<Type Name="PromptBehavior" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior">
  <TypeSignature Language="C#" Value="public enum PromptBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PromptBehavior extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Enum PromptBehavior" />
  <TypeSignature Language="F#" Value="type PromptBehavior = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Gibt an, ob AcquireToken nur bei Bedarf automatisch auffordern soll, oder gibt an, ob die Warnung unabhängig davon, ob anzeigen soll ein zwischengespeichertes Token vorhanden ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Always">
      <MemberSignature Language="C#" Value="Always" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Always = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberSignature Language="VB.NET" Value="Always" />
      <MemberSignature Language="F#" Value="Always = 1" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Always" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Benutzer wird zum Eingeben von Anmeldeinformationen aufgefordert werden, auch wenn es ein Token, das die bereits im Cache erfüllt.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Auto">
      <MemberSignature Language="C#" Value="Auto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Auto = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberSignature Language="VB.NET" Value="Auto" />
      <MemberSignature Language="F#" Value="Auto = 0" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Auto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Erwerben Token wird der Benutzer zum Eingeben von Anmeldeinformationen nur bei Bedarf aufgefordert.  Wenn ein Token, das die Anforderungen erfüllt bereits zwischengespeichert wird wird der Benutzer nicht aufgefordert werden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Never">
      <MemberSignature Language="C#" Value="Never" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior Never = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberSignature Language="VB.NET" Value="Never" />
      <MemberSignature Language="F#" Value="Never = 2" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.Never" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Benutzer wird nicht zum Eingeben von Anmeldeinformationen aufgefordert werden.  Wenn eine Bestätigung erforderlich ist, wird die AcquireToken-Anforderung fehl.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RefreshSession">
      <MemberSignature Language="C#" Value="RefreshSession" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior RefreshSession = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberSignature Language="VB.NET" Value="RefreshSession" />
      <MemberSignature Language="F#" Value="RefreshSession = 3" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.RefreshSession" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            (Über das Anzeigen von Webview) erneut autorisiert die Ressourcenverwendung, stellen Sie sicher, dass das resultierende Zugriffstoken aktualisierte Ansprüche enthält. Wenn Benutzer Anmeldung Cookies zur Verfügung stehen, die Benutzer werden nicht erneut zum Eingeben von Anmeldeinformationen aufgefordert und das Anmeldedialogfeld wird automatisch verworfen werden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SelectAccount">
      <MemberSignature Language="C#" Value="SelectAccount" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior SelectAccount = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberSignature Language="VB.NET" Value="SelectAccount" />
      <MemberSignature Language="F#" Value="SelectAccount = 4" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior.SelectAccount" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.PromptBehavior</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            Der Benutzer aufgefordert, ein Benutzerkonto auswählen, auch wenn es ein Token, das die bereits im Cache erfüllt. Dadurch wird einen Benutzer verfügt über mehrere Konten auf dem Autorisierungsserver für mehrere Konten auswählen, die sie möglicherweise die aktuellen Sitzungen für verfügen. 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>